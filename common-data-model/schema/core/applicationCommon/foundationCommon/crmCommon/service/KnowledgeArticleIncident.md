---
title: KnowledgeArticleIncident - Common Data Model | Microsoft Docs
description: Association between an knowledge article and incident.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Knowledge Article Incident

Association between an knowledge article and incident.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/service/KnowledgeArticleIncident.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/service/KnowledgeArticleIncident  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[ownerId](#ownerId)|Owner Id|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[knowledgeArticleIncidentId](#knowledgeArticleIncidentId)|Unique identifier of the Knowledge Article for the incident.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[incidentId](#incidentId)|Choose the Incident id for the knowledge article.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[knowledgearticleId](#knowledgearticleId)|Choose the Knowledge Article.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[knowledgeUsage](#knowledgeUsage)|Knowledge Usage.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[knowledgeUsage_display](#knowledgeUsage_display)||<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[isSentToCustomer](#isSentToCustomer)|This should be set to Yes when the user emails the article link to a customer. |<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[stateCode](#stateCode)|Status of the Knowledge Article Incident|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[stateCode_display](#stateCode_display)||<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[statusCode](#statusCode)|Reason for the status of the Knowledge Article Incident|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[statusCode_display](#statusCode_display)||<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="KnowledgeArticleIncident.md" target="_blank">service/KnowledgeArticleIncident</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#knowledgeArticleIncidentId name="knowledgeArticleIncidentId">knowledgeArticleIncidentId</a>

Unique identifier of the Knowledge Article for the incident.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>KnowledgeArticle Incident</td></tr><tr><td>description</td><td>Unique identifier of the Knowledge Article for the incident.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>knowledgearticleincidentid</td></tr></table>

### <a href=#incidentId name="incidentId">incidentId</a>

Choose the Incident id for the knowledge article.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Incident</td></tr><tr><td>description</td><td>Choose the Incident id for the knowledge article.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>incidentid</td></tr></table>

### <a href=#knowledgearticleId name="knowledgearticleId">knowledgearticleId</a>

Choose the Knowledge Article.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Knowledge Article</td></tr><tr><td>description</td><td>Choose the Knowledge Article.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>knowledgearticleid</td></tr></table>

### <a href=#knowledgeUsage name="knowledgeUsage">knowledgeUsage</a>

Knowledge Usage.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Knowledge Usage </td></tr><tr><td>description</td><td>Knowledge Usage.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>knowledgeusage</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Reference</td><td>1</td></tr><tr><td>en</td><td>Solution</td><td>2</td></tr><tr><td>en</td><td>Source</td><td>3</td></tr></table></td></tr></table>

### <a href=#knowledgeUsage_display name="knowledgeUsage_display">knowledgeUsage_display</a>

First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isSentToCustomer name="isSentToCustomer">isSentToCustomer</a>

This should be set to Yes when the user emails the article link to a customer.   
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sent To Customer</td></tr><tr><td>description</td><td>This should be set to Yes when the user emails the article link to a customer. </td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>issenttocustomer</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Knowledge Article Incident  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Knowledge Article Incident</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Knowledge Article Incident  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Knowledge Article Incident</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: service/KnowledgeArticleIncident (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>
