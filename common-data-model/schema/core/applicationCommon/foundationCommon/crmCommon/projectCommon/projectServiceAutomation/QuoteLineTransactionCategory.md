---
title: QuoteLineTransactionCategory - Common Data Model | Microsoft Docs
description: List of transaction categories that will be considered as costs when computing the profit of a quote line.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Quote Line Transaction Category

List of transaction categories that will be considered as costs when computing the profit of a quote line.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/QuoteLineTransactionCategory.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/QuoteLineTransactionCategory  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[ownerId](#ownerId)|Owner Id|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[quoteLineTransactionCategoryId](#quoteLineTransactionCategoryId)|Shows the entity instances.|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[stateCode](#stateCode)|Status of the Quote Line Transaction Category|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[stateCode_display](#stateCode_display)||<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[statusCode](#statusCode)|Reason for the status of the Quote Line Transaction Category|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[statusCode_display](#statusCode_display)||<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[description](#description)|Type the name of the custom entity.|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[billingType](#billingType)|Select whether the transaction category will be charged to the customer. Valid values are Chargeable, Non-chargeable, Complimentary. Project transactions in chargeable categories only will affect the total on the eventual invoice|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[billingType_display](#billingType_display)||<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[quoteLine](#quoteLine)|(Deprecated) Quote line corresponding to this record|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[quoteLineId](#quoteLineId)|Unique identifier for Quote Line associated with Quote Line Transaction Category.|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[quoteLineTransactionClassification](#quoteLineTransactionClassification)|Select the transaction classification on the quote line. 4 classifications are supported: Select the time, Expense, Material and Fee. For Fixed price quote lines, milestone transaction type is also supported|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[transactionCategory](#transactionCategory)|Shows the transaction classification for this quote line.|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[transactionClassification](#transactionClassification)|Transaction type corresponding to this record|<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|
|[transactionClassification_display](#transactionClassification_display)||<a href="QuoteLineTransactionCategory.md" target="_blank">projectServiceAutomation/QuoteLineTransactionCategory</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#quoteLineTransactionCategoryId name="quoteLineTransactionCategoryId">quoteLineTransactionCategoryId</a>

Shows the entity instances.  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote Line Transaction Category</td></tr><tr><td>description</td><td>Shows the entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_quotelinetransactioncategoryid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Quote Line Transaction Category  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Quote Line Transaction Category</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Quote Line Transaction Category  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Quote Line Transaction Category</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

Type the name of the custom entity.  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_description</td></tr></table>

### <a href=#billingType name="billingType">billingType</a>

Select whether the transaction category will be charged to the customer. Valid values are Chargeable, Non-chargeable, Complimentary. Project transactions in chargeable categories only will affect the total on the eventual invoice  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing Type</td></tr><tr><td>description</td><td>Select whether the transaction category will be charged to the customer. Valid values are Chargeable, Non-chargeable, Complimentary. Project transactions in chargeable categories only will affect the total on the eventual invoice</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_billingtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Non Chargeable</td><td>192350000</td></tr><tr><td>en</td><td>Chargeable</td><td>192350001</td></tr><tr><td>en</td><td>Complimentary</td><td>192350002</td></tr><tr><td>en</td><td>Not Available</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#billingType_display name="billingType_display">billingType_display</a>

First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#quoteLine name="quoteLine">quoteLine</a>

(Deprecated) Quote line corresponding to this record  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>(Deprecated) Quote Line</td></tr><tr><td>description</td><td>(Deprecated) Quote line corresponding to this record</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_quoteline</td></tr></table>

### <a href=#quoteLineId name="quoteLineId">quoteLineId</a>

Unique identifier for Quote Line associated with Quote Line Transaction Category.  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote Line</td></tr><tr><td>description</td><td>Unique identifier for Quote Line associated with Quote Line Transaction Category.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_quotelineid</td></tr></table>

### <a href=#quoteLineTransactionClassification name="quoteLineTransactionClassification">quoteLineTransactionClassification</a>

Select the transaction classification on the quote line. 4 classifications are supported: Select the time, Expense, Material and Fee. For Fixed price quote lines, milestone transaction type is also supported  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote Line Transaction Classification</td></tr><tr><td>description</td><td>Select the transaction classification on the quote line. 4 classifications are supported: Select the time, Expense, Material and Fee. For Fixed price quote lines, milestone transaction type is also supported</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_quotelinetransactionclassification</td></tr></table>

### <a href=#transactionCategory name="transactionCategory">transactionCategory</a>

Shows the transaction classification for this quote line.  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Category</td></tr><tr><td>description</td><td>Shows the transaction classification for this quote line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactioncategory</td></tr></table>

### <a href=#transactionClassification name="transactionClassification">transactionClassification</a>

Transaction type corresponding to this record  
First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Classification</td></tr><tr><td>description</td><td>Transaction type corresponding to this record</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactionclassification</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Time</td><td>192350000</td></tr><tr><td>en</td><td>Expense</td><td>192350001</td></tr><tr><td>en</td><td>Material</td><td>192350002</td></tr><tr><td>en</td><td>Milestone</td><td>192350003</td></tr><tr><td>en</td><td>Fee</td><td>192350004</td></tr><tr><td>en</td><td>Tax</td><td>690970002</td></tr></table></td></tr></table>

### <a href=#transactionClassification_display name="transactionClassification_display">transactionClassification_display</a>

First included in: projectServiceAutomation/QuoteLineTransactionCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
