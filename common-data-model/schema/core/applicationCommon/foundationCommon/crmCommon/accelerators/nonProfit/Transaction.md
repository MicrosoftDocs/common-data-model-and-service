---
title: Transaction - Common Data Model | Microsoft Docs
description: This describes the Transaction entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Transaction

Transactions (also referred to as donations) represent payments from a constituent (i.e. donor, contact, account or organization) to the nonprofit.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/Transaction.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/Transaction  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[transactionId](#transactionId)|Unique identifier for entity instances|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[stateCode](#stateCode)|Status of the Transaction|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[stateCode_display](#stateCode_display)||<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[statusCode](#statusCode)|Reason for the status of the Transaction|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[statusCode_display](#statusCode_display)||<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[name](#name)||<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[adjustmentComment](#adjustmentComment)|Any notes or details about the adjustment that the user may have optionally entered.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[adjustmentReason](#adjustmentReason)||<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[adjustmentReason_display](#adjustmentReason_display)||<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[adjustmentType](#adjustmentType)||<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[adjustmentType_display](#adjustmentType_display)||<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[amount](#amount)||<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[amountBase](#amountBase)|Value of the Amount in base currency.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[anonymity](#anonymity)||<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[anonymity_display](#anonymity_display)||<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[bookDate](#bookDate)||<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[dataEntryReference](#dataEntryReference)|Tracks data origin of payment transactions. References may be channel-specific.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[dataEntrySource](#dataEntrySource)||<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[dataEntrySource_display](#dataEntrySource_display)||<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[effectiveCampaignId](#effectiveCampaignId)|Effective Campaign|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[effectiveSourceCode](#effectiveSourceCode)||<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[exchangeRateDate](#exchangeRateDate)|The date and time at which the currency exchange rate was determined|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[isAdjusted](#isAdjusted)|Indicates that this transaction has been adjusted by a later transaction.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[originalTxnAdjustedId](#originalTxnAdjustedId)|Original Transaction Adjusted|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[originatingCampaignId](#originatingCampaignId)|Originating Campaign|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[originatingSourceCode](#originatingSourceCode)|The marketing segmentation source code.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[postedDate](#postedDate)||<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[receivedDate](#receivedDate)||<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[transactionPaymentMethodId](#transactionPaymentMethodId)|Payment Method|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[transactionPaymentScheduleId](#transactionPaymentScheduleId)|Payment Schedule|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[transactionReceiptOnAccountId](#transactionReceiptOnAccountId)|Receipt On Account|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[currencyValueDate](#currencyValueDate)|The date on which the transaction was made or agreed.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[description](#description)|A description of the transaction.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[disbursementChannelId](#disbursementChannelId)|The channel through which the funds will flow for this transaction.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[financeTypeId](#financeTypeId)|The type of finance (e.g. grant, loan, debt relief, etc.).|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[flowTypeId](#flowTypeId)|Whether the transaction is funded by Official Development Assistance (ODA), Other Official Flows (OOF), etc.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[humanitarian](#humanitarian)|Indicates that this transaction relates entirely or partially to humanitarian aid.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[providerActivityIdentifier](#providerActivityIdentifier)|If incoming funds are being provided from the budget of another activity, record the activity's unique identifier.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[providerOrganizationId](#providerOrganizationId)|The organization from which the transaction originated.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[recipientActivityIdentifier](#recipientActivityIdentifier)|If outgoing funds are being provided to another activity, record the activity's unique identifier.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[recipientCountryDescription](#recipientCountryDescription)|A description of the recipient country.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[recipientCountryId](#recipientCountryId)|A country that will benefit from this transaction.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[recipientOrganizationId](#recipientOrganizationId)|The organization receiving the money from the transaction.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[recipientRegionDescription](#recipientRegionDescription)|A description of the recipient region.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[recipientRegionId](#recipientRegionId)|A region that will benefit from this transaction.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|
|[tiedStatusId](#tiedStatusId)|Whether the aid is untied, tied, or partially tied.|<a href="Transaction.md" target="_blank">nonProfit/Transaction</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#transactionId name="transactionId">transactionId</a>

Unique identifier for entity instances  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_transactionid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Transaction  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Transaction</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Transaction  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Transaction</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#adjustmentComment name="adjustmentComment">adjustmentComment</a>

Any notes or details about the adjustment that the user may have optionally entered.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjustment Comment</td></tr><tr><td>description</td><td>Any notes or details about the adjustment that the user may have optionally entered.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_adjustmentcomment</td></tr></table>

### <a href=#adjustmentReason name="adjustmentReason">adjustmentReason</a>

First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjustment Reason</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_adjustmentreason</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>AdjustmentReasonOption</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#adjustmentReason_display name="adjustmentReason_display">adjustmentReason_display</a>

First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#adjustmentType name="adjustmentType">adjustmentType</a>

First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjustment Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_adjustmenttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>AdjustmentTypeOption</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#adjustmentType_display name="adjustmentType_display">adjustmentType_display</a>

First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#amount name="amount">amount</a>

First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amountBase name="amountBase">amountBase</a>

Value of the Amount in base currency.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base)</td></tr><tr><td>description</td><td>Value of the Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amount_base</td></tr></table>

### <a href=#anonymity name="anonymity">anonymity</a>

First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Anonymity</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_anonymity</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Anonymity</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#anonymity_display name="anonymity_display">anonymity_display</a>

First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#bookDate name="bookDate">bookDate</a>

First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Book Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_bookdate</td></tr></table>

### <a href=#dataEntryReference name="dataEntryReference">dataEntryReference</a>

Tracks data origin of payment transactions. References may be channel-specific.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Data Entry Reference</td></tr><tr><td>description</td><td>Tracks data origin of payment transactions. References may be channel-specific.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_dataentryreference</td></tr></table>

### <a href=#dataEntrySource name="dataEntrySource">dataEntrySource</a>

First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Data Entry Source</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_dataentrysource</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>DataEntryType</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#dataEntrySource_display name="dataEntrySource_display">dataEntrySource_display</a>

First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#effectiveCampaignId name="effectiveCampaignId">effectiveCampaignId</a>

Effective Campaign  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effective Campaign</td></tr><tr><td>description</td><td>Effective Campaign</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_effectivecampaignid</td></tr></table>

### <a href=#effectiveSourceCode name="effectiveSourceCode">effectiveSourceCode</a>

First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effective Source Code</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_effectivesourcecode</td></tr></table>

### <a href=#exchangeRateDate name="exchangeRateDate">exchangeRateDate</a>

The date and time at which the currency exchange rate was determined  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate Date</td></tr><tr><td>description</td><td>The date and time at which the currency exchange rate was determined</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_exchangeratedate</td></tr></table>

### <a href=#isAdjusted name="isAdjusted">isAdjusted</a>

Indicates that this transaction has been adjusted by a later transaction.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Adjusted</td></tr><tr><td>description</td><td>Indicates that this transaction has been adjusted by a later transaction.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_isadjusted</td></tr></table>

### <a href=#originalTxnAdjustedId name="originalTxnAdjustedId">originalTxnAdjustedId</a>

Original Transaction Adjusted  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Original Transaction Adjusted</td></tr><tr><td>description</td><td>Original Transaction Adjusted</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_originaltxnadjustedid</td></tr></table>

### <a href=#originatingCampaignId name="originatingCampaignId">originatingCampaignId</a>

Originating Campaign  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Originating Campaign</td></tr><tr><td>description</td><td>Originating Campaign</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_originatingcampaignid</td></tr></table>

### <a href=#originatingSourceCode name="originatingSourceCode">originatingSourceCode</a>

The marketing segmentation source code.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Originating Source Code</td></tr><tr><td>description</td><td>The marketing segmentation source code.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_originatingsourcecode</td></tr></table>

### <a href=#postedDate name="postedDate">postedDate</a>

First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Posted Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_posteddate</td></tr></table>

### <a href=#receivedDate name="receivedDate">receivedDate</a>

First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Received Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_receiveddate</td></tr></table>

### <a href=#transactionPaymentMethodId name="transactionPaymentMethodId">transactionPaymentMethodId</a>

Payment Method  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment Method</td></tr><tr><td>description</td><td>Payment Method</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_transaction_paymentmethodid</td></tr></table>

### <a href=#transactionPaymentScheduleId name="transactionPaymentScheduleId">transactionPaymentScheduleId</a>

Payment Schedule  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment Schedule</td></tr><tr><td>description</td><td>Payment Schedule</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_transaction_paymentscheduleid</td></tr></table>

### <a href=#transactionReceiptOnAccountId name="transactionReceiptOnAccountId">transactionReceiptOnAccountId</a>

Receipt On Account  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receipt On Account</td></tr><tr><td>description</td><td>Receipt On Account</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_transaction_receiptonaccountid</td></tr></table>

### <a href=#currencyValueDate name="currencyValueDate">currencyValueDate</a>

The date on which the transaction was made or agreed.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency Value Date</td></tr><tr><td>description</td><td>The date on which the transaction was made or agreed.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_currencyvaluedate</td></tr></table>

### <a href=#description name="description">description</a>

A description of the transaction.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>A description of the transaction.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_description</td></tr></table>

### <a href=#disbursementChannelId name="disbursementChannelId">disbursementChannelId</a>

The channel through which the funds will flow for this transaction.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disbursement Channel</td></tr><tr><td>description</td><td>The channel through which the funds will flow for this transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_disbursementchannelid</td></tr></table>

### <a href=#financeTypeId name="financeTypeId">financeTypeId</a>

The type of finance (e.g. grant, loan, debt relief, etc.).  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Finance Type</td></tr><tr><td>description</td><td>The type of finance (e.g. grant, loan, debt relief, etc.).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_financetypeid</td></tr></table>

### <a href=#flowTypeId name="flowTypeId">flowTypeId</a>

Whether the transaction is funded by Official Development Assistance (ODA), Other Official Flows (OOF), etc.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Flow Type</td></tr><tr><td>description</td><td>Whether the transaction is funded by Official Development Assistance (ODA), Other Official Flows (OOF), etc.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_flowtypeid</td></tr></table>

### <a href=#humanitarian name="humanitarian">humanitarian</a>

Indicates that this transaction relates entirely or partially to humanitarian aid.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Humanitarian</td></tr><tr><td>description</td><td>Indicates that this transaction relates entirely or partially to humanitarian aid.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_humanitarian</td></tr></table>

### <a href=#providerActivityIdentifier name="providerActivityIdentifier">providerActivityIdentifier</a>

If incoming funds are being provided from the budget of another activity, record the activity's unique identifier.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Provider Activity Identifier</td></tr><tr><td>description</td><td>If incoming funds are being provided from the budget of another activity, record the activity's unique identifier.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_provideractivityidentifier</td></tr></table>

### <a href=#providerOrganizationId name="providerOrganizationId">providerOrganizationId</a>

The organization from which the transaction originated.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Provider Organization</td></tr><tr><td>description</td><td>The organization from which the transaction originated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_provideriorganizationid</td></tr></table>

### <a href=#recipientActivityIdentifier name="recipientActivityIdentifier">recipientActivityIdentifier</a>

If outgoing funds are being provided to another activity, record the activity's unique identifier.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Activity Identifier</td></tr><tr><td>description</td><td>If outgoing funds are being provided to another activity, record the activity's unique identifier.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientactivityidentifier</td></tr></table>

### <a href=#recipientCountryDescription name="recipientCountryDescription">recipientCountryDescription</a>

A description of the recipient country.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Country Description</td></tr><tr><td>description</td><td>A description of the recipient country.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientcountrydescription</td></tr></table>

### <a href=#recipientCountryId name="recipientCountryId">recipientCountryId</a>

A country that will benefit from this transaction.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Country</td></tr><tr><td>description</td><td>A country that will benefit from this transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientcountryid</td></tr></table>

### <a href=#recipientOrganizationId name="recipientOrganizationId">recipientOrganizationId</a>

The organization receiving the money from the transaction.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Organization</td></tr><tr><td>description</td><td>The organization receiving the money from the transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientorganizationid</td></tr></table>

### <a href=#recipientRegionDescription name="recipientRegionDescription">recipientRegionDescription</a>

A description of the recipient region.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Region Description</td></tr><tr><td>description</td><td>A description of the recipient region.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientregiondescription</td></tr></table>

### <a href=#recipientRegionId name="recipientRegionId">recipientRegionId</a>

A region that will benefit from this transaction.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Region</td></tr><tr><td>description</td><td>A region that will benefit from this transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientregionid</td></tr></table>

### <a href=#tiedStatusId name="tiedStatusId">tiedStatusId</a>

Whether the aid is untied, tied, or partially tied.  
First included in: nonProfit/Transaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tied Status</td></tr><tr><td>description</td><td>Whether the aid is untied, tied, or partially tied.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_tiedstatusid</td></tr></table>
