---
title: KnowledgeBaseRecord - Common Data Model | Microsoft Docs
description: Metadata of knowledge base (KB) articles associated with Microsoft Dynamics 365 entities.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Knowledge Base Record

Metadata of knowledge base (KB) articles associated with Microsoft Dynamics 365 entities.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/KnowledgeBaseRecord.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /KnowledgeBaseRecord  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[knowledgeBaseRecordId](#knowledgeBaseRecordId)|This field will be used to store the Unique ID of the associated Knowledge Base records|<a href="KnowledgeBaseRecord.md" target="_blank">applicationCommon/KnowledgeBaseRecord</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="KnowledgeBaseRecord.md" target="_blank">applicationCommon/KnowledgeBaseRecord</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="KnowledgeBaseRecord.md" target="_blank">applicationCommon/KnowledgeBaseRecord</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="KnowledgeBaseRecord.md" target="_blank">applicationCommon/KnowledgeBaseRecord</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="KnowledgeBaseRecord.md" target="_blank">applicationCommon/KnowledgeBaseRecord</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="KnowledgeBaseRecord.md" target="_blank">applicationCommon/KnowledgeBaseRecord</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="KnowledgeBaseRecord.md" target="_blank">applicationCommon/KnowledgeBaseRecord</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="KnowledgeBaseRecord.md" target="_blank">applicationCommon/KnowledgeBaseRecord</a>|
|[versionNumber](#versionNumber)||<a href="KnowledgeBaseRecord.md" target="_blank">applicationCommon/KnowledgeBaseRecord</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="KnowledgeBaseRecord.md" target="_blank">applicationCommon/KnowledgeBaseRecord</a>|
|[title](#title)|Shows the title of the knowledge base (KB) Record.|<a href="KnowledgeBaseRecord.md" target="_blank">applicationCommon/KnowledgeBaseRecord</a>|
|[privateUrl](#privateUrl)|Shows the internal Parature service desk URL of the knowledge base records.|<a href="KnowledgeBaseRecord.md" target="_blank">applicationCommon/KnowledgeBaseRecord</a>|
|[publicUrl](#publicUrl)|Shows the public Parature portal URL of the knowledge base records.|<a href="KnowledgeBaseRecord.md" target="_blank">applicationCommon/KnowledgeBaseRecord</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the knowledge base record with respect to the base currency.|<a href="KnowledgeBaseRecord.md" target="_blank">applicationCommon/KnowledgeBaseRecord</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Exchange rate for the currency associated with the Knowledge Base Record with respect to the base currency.|<a href="KnowledgeBaseRecord.md" target="_blank">applicationCommon/KnowledgeBaseRecord</a>|
|[uniqueId](#uniqueId)|Shows the unique ID of the linked knowledge base (KB) article.|<a href="KnowledgeBaseRecord.md" target="_blank">applicationCommon/KnowledgeBaseRecord</a>|

### <a href=#knowledgeBaseRecordId name="knowledgeBaseRecordId">knowledgeBaseRecordId</a>

This field will be used to store the Unique ID of the associated Knowledge Base records  
First included in: applicationCommon/KnowledgeBaseRecord (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ID</td></tr><tr><td>description</td><td>This field will be used to store the Unique ID of the associated Knowledge Base records</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>knowledgebaserecordid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: applicationCommon/KnowledgeBaseRecord (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: applicationCommon/KnowledgeBaseRecord (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: applicationCommon/KnowledgeBaseRecord (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: applicationCommon/KnowledgeBaseRecord (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: applicationCommon/KnowledgeBaseRecord (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: applicationCommon/KnowledgeBaseRecord (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: applicationCommon/KnowledgeBaseRecord (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

First included in: applicationCommon/KnowledgeBaseRecord (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: applicationCommon/KnowledgeBaseRecord (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#title name="title">title</a>

Shows the title of the knowledge base (KB) Record.  
First included in: applicationCommon/KnowledgeBaseRecord (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>KB Record Title</td></tr><tr><td>description</td><td>Shows the title of the knowledge base (KB) Record.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>title</td></tr></table>

### <a href=#privateUrl name="privateUrl">privateUrl</a>

Shows the internal Parature service desk URL of the knowledge base records.  
First included in: applicationCommon/KnowledgeBaseRecord (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Private URL</td></tr><tr><td>description</td><td>Shows the internal Parature service desk URL of the knowledge base records.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>privateurl</td></tr></table>

### <a href=#publicUrl name="publicUrl">publicUrl</a>

Shows the public Parature portal URL of the knowledge base records.  
First included in: applicationCommon/KnowledgeBaseRecord (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Public URL</td></tr><tr><td>description</td><td>Shows the public Parature portal URL of the knowledge base records.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>publicurl</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the knowledge base record with respect to the base currency.  
First included in: applicationCommon/KnowledgeBaseRecord (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ExchangeRate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the knowledge base record with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Exchange rate for the currency associated with the Knowledge Base Record with respect to the base currency.  
First included in: applicationCommon/KnowledgeBaseRecord (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the Knowledge Base Record with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#uniqueId name="uniqueId">uniqueId</a>

Shows the unique ID of the linked knowledge base (KB) article.  
First included in: applicationCommon/KnowledgeBaseRecord (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unique ID</td></tr><tr><td>description</td><td>Shows the unique ID of the linked knowledge base (KB) article.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>uniqueid</td></tr></table>
