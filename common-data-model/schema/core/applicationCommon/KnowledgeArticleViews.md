---
title: KnowledgeArticleViews - Common Data Model | Microsoft Docs
description: No of times an article is viewed per day
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Knowledge Article Views

No of times an article is viewed per day  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/KnowledgeArticleViews.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /KnowledgeArticleViews  
- [/foundationCommon/crmCommon/solutions/portals/KnowledgeArticleViews](foundationCommon/crmCommon/solutions/portals/KnowledgeArticleViews.md "/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/KnowledgeArticleViews.cdm.json/KnowledgeArticleViews")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[knowledgeArticleViewsId](#knowledgeArticleViewsId)|Unique identifier of the Knowledge Article Views|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[versionNumber](#versionNumber)||<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[knowledgeArticleView](#knowledgeArticleView)|Number of Knowledge Article Views visited per day|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[viewDate](#viewDate)|Information about the Day|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[knowledgearticleId](#knowledgearticleId)|Choose the Knowledge Article.|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[modifiedOn](#modifiedOn)|Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[ownerId](#ownerId)|Owner Id|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier of the business unit that owns the knowledge article views.|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[owningUser](#owningUser)|Unique identifier of the user who owns the knowledge article views.|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[stateCode](#stateCode)|Status of the Knowledge Article Views|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[stateCode_display](#stateCode_display)||<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[statusCode](#statusCode)|Reason for the status of the Knowledge Article Views|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[statusCode_display](#statusCode_display)||<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[location](#location)|Shows where the knowledge was used|<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|
|[location_display](#location_display)||<a href="KnowledgeArticleViews.md" target="_blank">applicationCommon/KnowledgeArticleViews</a>|

### <a href=#knowledgeArticleViewsId name="knowledgeArticleViewsId">knowledgeArticleViewsId</a>

Unique identifier of the Knowledge Article Views  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>View</td></tr><tr><td>description</td><td>Unique identifier of the Knowledge Article Views</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>knowledgearticleviewsid</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#knowledgeArticleView name="knowledgeArticleView">knowledgeArticleView</a>

Number of Knowledge Article Views visited per day  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Knowledge Article View</td></tr><tr><td>description</td><td>Number of Knowledge Article Views visited per day</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>knowledgearticleview</td></tr></table>

### <a href=#viewDate name="viewDate">viewDate</a>

Information about the Day  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Day</td></tr><tr><td>description</td><td>Information about the Day</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>viewdate</td></tr></table>

### <a href=#knowledgearticleId name="knowledgearticleId">knowledgearticleId</a>

Choose the Knowledge Article.  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Knowledge Article</td></tr><tr><td>description</td><td>Choose the Knowledge Article.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>knowledgearticleid</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Shows the date and time when the record was last updated. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier of the business unit that owns the knowledge article views.  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier of the business unit that owns the knowledge article views.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user who owns the knowledge article views.  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user who owns the knowledge article views.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Knowledge Article Views  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Knowledge Article Views</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Knowledge Article Views  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Knowledge Article Views</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#location name="location">location</a>

Shows where the knowledge was used  
First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Location</td></tr><tr><td>description</td><td>Shows where the knowledge was used</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>location</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Internal</td><td>1</td></tr><tr><td>en</td><td>Web</td><td>2</td></tr></table></td></tr></table>

### <a href=#location_display name="location_display">location_display</a>

First included in: applicationCommon/KnowledgeArticleViews (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
