---
title: QuoteLineTransactionClassification - Common Data Model | Microsoft Docs
description: This describes the QuoteLineTransactionClassification entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Quote Line Transaction Classification

List of transaction classification heads, the four broad cost classifications of time, expense, material, and fee, that will be considered as costs when computing the profit of a quote line.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/QuoteLineTransactionClassification.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/QuoteLineTransactionClassification  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[ownerId](#ownerId)|Owner Id|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[quoteLineTransactionClassificationId](#quoteLineTransactionClassificationId)|Unique identifier for entity instances|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[stateCode](#stateCode)|Status of the Quote Line Transaction Classification|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[stateCode_display](#stateCode_display)||<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[statusCode](#statusCode)|Reason for the status of the Quote Line Transaction Classification|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[statusCode_display](#statusCode_display)||<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[description](#description)|Type the name of the custom entity.|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[billingType](#billingType)|Select whether the transaction classification identified on the quote line will be charged to the customer or not. Valid values are Chargeable, Non-chargeable and Complimentary.  |<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[billingType_display](#billingType_display)||<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[include](#include)||<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[quoteLine](#quoteLine)|(Deprecated) Type the reference to the Quote line to which this transaction classification is being associated to.|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[quoteLineId](#quoteLineId)|Unique identifier for Quote Line associated with Quote Line Transaction Classification.|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[transactionClassification](#transactionClassification)|Select the transaction classification on the quote line. 4 classifications are supported: Select the time, Expense, Material and Fee.|<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|
|[transactionClassification_display](#transactionClassification_display)||<a href="QuoteLineTransactionClassification.md" target="_blank">projectServiceAutomation/QuoteLineTransactionClassification</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#quoteLineTransactionClassificationId name="quoteLineTransactionClassificationId">quoteLineTransactionClassificationId</a>

Unique identifier for entity instances  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote Line Transaction Classification</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_quotelinetransactionclassificationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Quote Line Transaction Classification  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Quote Line Transaction Classification</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Quote Line Transaction Classification  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Quote Line Transaction Classification</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

Type the name of the custom entity.  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_description</td></tr></table>

### <a href=#billingType name="billingType">billingType</a>

Select whether the transaction classification identified on the quote line will be charged to the customer or not. Valid values are Chargeable, Non-chargeable and Complimentary.    
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing Type</td></tr><tr><td>description</td><td>Select whether the transaction classification identified on the quote line will be charged to the customer or not. Valid values are Chargeable, Non-chargeable and Complimentary.  </td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_billingtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Non Chargeable</td><td>192350000</td></tr><tr><td>en</td><td>Chargeable</td><td>192350001</td></tr><tr><td>en</td><td>Complimentary</td><td>192350002</td></tr><tr><td>en</td><td>Not Available</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#billingType_display name="billingType_display">billingType_display</a>

First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#include name="include">include</a>

First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_include</td></tr></table>

### <a href=#quoteLine name="quoteLine">quoteLine</a>

(Deprecated) Type the reference to the Quote line to which this transaction classification is being associated to.  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>(Deprecated) Quote Line</td></tr><tr><td>description</td><td>(Deprecated) Type the reference to the Quote line to which this transaction classification is being associated to.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_quoteline</td></tr></table>

### <a href=#quoteLineId name="quoteLineId">quoteLineId</a>

Unique identifier for Quote Line associated with Quote Line Transaction Classification.  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote Line</td></tr><tr><td>description</td><td>Unique identifier for Quote Line associated with Quote Line Transaction Classification.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_quotelineid</td></tr></table>

### <a href=#transactionClassification name="transactionClassification">transactionClassification</a>

Select the transaction classification on the quote line. 4 classifications are supported: Select the time, Expense, Material and Fee.  
First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Classification</td></tr><tr><td>description</td><td>Select the transaction classification on the quote line. 4 classifications are supported: Select the time, Expense, Material and Fee.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactionclassification</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Time</td><td>192350000</td></tr><tr><td>en</td><td>Expense</td><td>192350001</td></tr><tr><td>en</td><td>Material</td><td>192350002</td></tr><tr><td>en</td><td>Milestone</td><td>192350003</td></tr><tr><td>en</td><td>Fee</td><td>192350004</td></tr><tr><td>en</td><td>Tax</td><td>690970002</td></tr></table></td></tr></table>

### <a href=#transactionClassification_display name="transactionClassification_display">transactionClassification_display</a>

First included in: projectServiceAutomation/QuoteLineTransactionClassification (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
