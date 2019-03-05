---
title: DesignatedCredit - Common Data Model | Microsoft Docs
description: This describes the DesignatedCredit entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Designated Credit

A segment of a donation payment or in-kind gift that indicating the partial amount that is hard- or soft-credited to a Customer and allocated to one Designation.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/DesignatedCredit.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/DesignatedCredit  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[ownerId](#ownerId)|Owner Id|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[designatedCreditId](#designatedCreditId)|Unique identifier for entity instances|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[stateCode](#stateCode)|Status of the Designated Credit|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[stateCode_display](#stateCode_display)||<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[statusCode](#statusCode)|Reason for the status of the Designated Credit|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[statusCode_display](#statusCode_display)||<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[name](#name)||<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[adjustmentComment](#adjustmentComment)|Any notes or details about the adjustment that the user may have optionally entered.|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[adjustmentReason](#adjustmentReason)||<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[adjustmentReason_display](#adjustmentReason_display)||<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[adjustmentType](#adjustmentType)||<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[adjustmentType_display](#adjustmentType_display)||<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[amount](#amount)|The amount of the credit|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[amountBase](#amountBase)|Value of the Amount in base currency.|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[applyToCommitmentPaymentDate](#applyToCommitmentPaymentDate)|When this credit accrues toward a donor commitment installment payment, this is the payment date toward which the credit accrues (even if the actual payment received was earlier or later)|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[bookDate](#bookDate)||<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[creditReason](#creditReason)|Dependent picklist based on CreditType|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[creditReason_display](#creditReason_display)||<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[creditType](#creditType)|Indicating whether this is a Hard, Soft, or Fundraiser credit; or other custom type|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[creditType_display](#creditType_display)||<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[dataEntryReference](#dataEntryReference)|Tracks data origin of payment transactions. References may be channel-specific.|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[dataEntrySource](#dataEntrySource)||<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[dataEntrySource_display](#dataEntrySource_display)||<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[exchangeRateDate](#exchangeRateDate)|The date and time at which the currency exchange rate was determined|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[isAdjusted](#isAdjusted)|Indicates that this DesignatedCredit has been adjusted by a later DesignatedCredit|<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[postedDate](#postedDate)||<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|
|[receivedDate](#receivedDate)||<a href="DesignatedCredit.md" target="_blank">nonProfit/DesignatedCredit</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#designatedCreditId name="designatedCreditId">designatedCreditId</a>

Unique identifier for entity instances  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Designated Credit</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_designatedcreditid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Designated Credit  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Designated Credit</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Designated Credit  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Designated Credit</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#adjustmentComment name="adjustmentComment">adjustmentComment</a>

Any notes or details about the adjustment that the user may have optionally entered.  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjustment Comment</td></tr><tr><td>description</td><td>Any notes or details about the adjustment that the user may have optionally entered.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_adjustmentcomment</td></tr></table>

### <a href=#adjustmentReason name="adjustmentReason">adjustmentReason</a>

First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjustment Reason</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_adjustmentreason</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>AdjustmentReasonOption</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#adjustmentReason_display name="adjustmentReason_display">adjustmentReason_display</a>

First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#adjustmentType name="adjustmentType">adjustmentType</a>

First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjustment Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_adjustmenttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>AdjustmentTypeOption</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#adjustmentType_display name="adjustmentType_display">adjustmentType_display</a>

First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#amount name="amount">amount</a>

The amount of the credit  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount</td></tr><tr><td>description</td><td>The amount of the credit</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amountBase name="amountBase">amountBase</a>

Value of the Amount in base currency.  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base)</td></tr><tr><td>description</td><td>Value of the Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amount_base</td></tr></table>

### <a href=#applyToCommitmentPaymentDate name="applyToCommitmentPaymentDate">applyToCommitmentPaymentDate</a>

When this credit accrues toward a donor commitment installment payment, this is the payment date toward which the credit accrues (even if the actual payment received was earlier or later)  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Apply To Commitment Payment Date</td></tr><tr><td>description</td><td>When this credit accrues toward a donor commitment installment payment, this is the payment date toward which the credit accrues (even if the actual payment received was earlier or later)</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_applytocommitmentpaymentdate</td></tr></table>

### <a href=#bookDate name="bookDate">bookDate</a>

First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Book Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_bookdate</td></tr></table>

### <a href=#creditReason name="creditReason">creditReason</a>

Dependent picklist based on CreditType  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit Reason</td></tr><tr><td>description</td><td>Dependent picklist based on CreditType</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_creditreason</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>CreditReasonOption</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#creditReason_display name="creditReason_display">creditReason_display</a>

First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#creditType name="creditType">creditType</a>

Indicating whether this is a Hard, Soft, or Fundraiser credit; or other custom type  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit Type</td></tr><tr><td>description</td><td>Indicating whether this is a Hard, Soft, or Fundraiser credit; or other custom type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_credittype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>CreditTypeOption</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#creditType_display name="creditType_display">creditType_display</a>

First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#dataEntryReference name="dataEntryReference">dataEntryReference</a>

Tracks data origin of payment transactions. References may be channel-specific.  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Data Entry Reference</td></tr><tr><td>description</td><td>Tracks data origin of payment transactions. References may be channel-specific.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_dataentryreference</td></tr></table>

### <a href=#dataEntrySource name="dataEntrySource">dataEntrySource</a>

First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Data Entry Source</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_dataentrysource</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>DataEntryType</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#dataEntrySource_display name="dataEntrySource_display">dataEntrySource_display</a>

First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#exchangeRateDate name="exchangeRateDate">exchangeRateDate</a>

The date and time at which the currency exchange rate was determined  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate Date</td></tr><tr><td>description</td><td>The date and time at which the currency exchange rate was determined</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_exchangeratedate</td></tr></table>

### <a href=#isAdjusted name="isAdjusted">isAdjusted</a>

Indicates that this DesignatedCredit has been adjusted by a later DesignatedCredit  
First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Adjusted</td></tr><tr><td>description</td><td>Indicates that this DesignatedCredit has been adjusted by a later DesignatedCredit</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_isadjusted</td></tr></table>

### <a href=#postedDate name="postedDate">postedDate</a>

First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Posted Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_posteddate</td></tr></table>

### <a href=#receivedDate name="receivedDate">receivedDate</a>

First included in: nonProfit/DesignatedCredit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Received Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_receiveddate</td></tr></table>
