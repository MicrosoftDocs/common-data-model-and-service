---
title: PaymentAsset - Common Data Model | Microsoft Docs
description: This describes the PaymentAsset entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Payment Asset

Specific types of payments, including in-kind gifts, stock and securities that are classified as assets require non-profits to follow specific reporting rules.  Managing these gifts tends to be very manual work for nonprofit development operations staff.  These gifts come in through a bank, must be manually reviewed and entered into a batch.  Often there are questions that need to be answered before a gift entry can be completed with ease.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/PaymentAsset.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/PaymentAsset  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[ownerId](#ownerId)|Owner Id|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[paymentAssetId](#paymentAssetId)|Unique identifier for entity instances|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[stateCode](#stateCode)|Status of the Payment Asset|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[stateCode_display](#stateCode_display)||<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[statusCode](#statusCode)|Reason for the status of the Payment Asset|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[statusCode_display](#statusCode_display)||<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[name](#name)||<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[amount](#amount)||<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[amountBase](#amountBase)|Value of the Amount in base currency.|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[assetType](#assetType)||<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[assetType_display](#assetType_display)||<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[bookDate](#bookDate)||<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[description](#description)||<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[originalAssetAdjustedId](#originalAssetAdjustedId)|Original Asset Gift Adjusted|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[paymentAssetPledgedAsset](#paymentAssetPledgedAsset)|Pledged Asset|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[paymentAssetCategory](#paymentAssetCategory)||<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[paymentAssetCategory_display](#paymentAssetCategory_display)||<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[paymentAssetSubcategory](#paymentAssetSubcategory)||<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[paymentAssetSubcategory_display](#paymentAssetSubcategory_display)||<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[pledgedOnPaymentScheduleId](#pledgedOnPaymentScheduleId)|Pledged On Payment Schedule|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[quantity](#quantity)||<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[symbol](#symbol)||<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|
|[transferredOnTransactionId](#transferredOnTransactionId)|Transferred On Transaction|<a href="PaymentAsset.md" target="_blank">nonProfit/PaymentAsset</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#paymentAssetId name="paymentAssetId">paymentAssetId</a>

Unique identifier for entity instances  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment Asset</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_paymentassetid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Payment Asset  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Payment Asset</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Payment Asset  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Payment Asset</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#amount name="amount">amount</a>

First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amountBase name="amountBase">amountBase</a>

Value of the Amount in base currency.  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base)</td></tr><tr><td>description</td><td>Value of the Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amount_base</td></tr></table>

### <a href=#assetType name="assetType">assetType</a>

First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Asset Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_assettype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>PaymentAssetType</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#assetType_display name="assetType_display">assetType_display</a>

First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#bookDate name="bookDate">bookDate</a>

First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Book Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_bookdate</td></tr></table>

### <a href=#description name="description">description</a>

First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_description</td></tr></table>

### <a href=#originalAssetAdjustedId name="originalAssetAdjustedId">originalAssetAdjustedId</a>

Original Asset Gift Adjusted  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Original Asset Gift Adjusted</td></tr><tr><td>description</td><td>Original Asset Gift Adjusted</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_originalassetadjustedid</td></tr></table>

### <a href=#paymentAssetPledgedAsset name="paymentAssetPledgedAsset">paymentAssetPledgedAsset</a>

Pledged Asset  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pledged Asset</td></tr><tr><td>description</td><td>Pledged Asset</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_paymentasset_pledgedasset</td></tr></table>

### <a href=#paymentAssetCategory name="paymentAssetCategory">paymentAssetCategory</a>

First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment Asset Category</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_paymentassetcategory</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>PaymentAssetCategory</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#paymentAssetCategory_display name="paymentAssetCategory_display">paymentAssetCategory_display</a>

First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#paymentAssetSubcategory name="paymentAssetSubcategory">paymentAssetSubcategory</a>

First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment Asset Subcategory</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_paymentassetsubcategory</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>PaymentAssetSubcategory</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#paymentAssetSubcategory_display name="paymentAssetSubcategory_display">paymentAssetSubcategory_display</a>

First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#pledgedOnPaymentScheduleId name="pledgedOnPaymentScheduleId">pledgedOnPaymentScheduleId</a>

Pledged On Payment Schedule  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pledged On Payment Schedule</td></tr><tr><td>description</td><td>Pledged On Payment Schedule</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_pledgedonpaymentscheduleid</td></tr></table>

### <a href=#quantity name="quantity">quantity</a>

First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_quantity</td></tr></table>

### <a href=#symbol name="symbol">symbol</a>

First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Symbol</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_symbol</td></tr></table>

### <a href=#transferredOnTransactionId name="transferredOnTransactionId">transferredOnTransactionId</a>

Transferred On Transaction  
First included in: nonProfit/PaymentAsset (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transferred On Transaction</td></tr><tr><td>description</td><td>Transferred On Transaction</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_transferredontransactionid</td></tr></table>
