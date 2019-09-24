---
title: Disbursement - Common Data Model | Microsoft Docs
description: This describes the Disbursement entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Disbursement

A Disbursement represents an Award disbursement to an individual or organizational awardee.  A Disbursement is related to a specific Award and Budget.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/Disbursement.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/Disbursement  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[disbursementId](#disbursementId)|Unique identifier for entity instances|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[stateCode](#stateCode)|Status of the Disbursement|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[stateCode_display](#stateCode_display)||<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[statusCode](#statusCode)|Reason for the status of the Disbursement|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[statusCode_display](#statusCode_display)||<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[name](#name)|The name of the custom entity.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[adjustmentComment](#adjustmentComment)|Any notes or details about the adjustment that the user may have optionally entered.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[adjustmentReason](#adjustmentReason)||<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[adjustmentReason_display](#adjustmentReason_display)||<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[adjustmentType](#adjustmentType)||<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[adjustmentType_display](#adjustmentType_display)||<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[adjustsOriginalTransactionId](#adjustsOriginalTransactionId)|Adjusts Original Transaction|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[amouont](#amouont)|The amount of the Disbursement.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[amouontBase](#amouontBase)|Value of the Amount in base currency.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[awardId](#awardId)|Award|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[bookDate](#bookDate)|Book Date|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[comment](#comment)|Comments about the Disbursement.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[description](#description)|Description of the Disbursement.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[isAdjusted](#isAdjusted)|Is Adjusted|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[postedDate](#postedDate)|The date the Disbursement was posted to the GL|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[recipientAccountId](#recipientAccountId)|Recipient Account|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[recipientContactId](#recipientContactId)|Recipient Contact|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[requestDate](#requestDate)|The date the Disbursement was requested.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[scheduledDisbursementDate](#scheduledDisbursementDate)|The date the Disbursement is scheduled to be sent.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[sentDate](#sentDate)|The date the Disbursement was sent.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[status](#status)|Status of the Disbursement.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[status_display](#status_display)||<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[type](#type)|The type of Disbursement.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[type_display](#type_display)||<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[budgetType](#budgetType)|OECD DAC classification used to determine the character of resource flows (bilateral or multilateral)|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[budgetType_display](#budgetType_display)||<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[currencyValueDate](#currencyValueDate)|Date for the currency value|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[disbursementChannelId](#disbursementChannelId)|The channel through which the funds will flow for this transaction.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[financeTypeId](#financeTypeId)|The type of finance (e.g. grant, loan, debt relief, etc.).|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[flowTypeId](#flowTypeId)|Whether the transaction is funded by Official Development Assistance (ODA), Other Official Flows (OOF), etc.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[humanitarian](#humanitarian)|Indicates that this transaction relates entirely or partially to humanitarian aid.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[periodEnd](#periodEnd)|Date for the period end|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[periodStart](#periodStart)|Date for the period start|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[providerActivityIdentifier](#providerActivityIdentifier)|If incoming funds are being provided from the budget of another activity, record the activity's unique identifier.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[providerOrganizationId](#providerOrganizationId)|The organization from which the transaction originated.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[recipientActivityIdentifier](#recipientActivityIdentifier)|If outgoing funds are being provided to another activity, record the activity's unique identifier.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[recipientCountryDescription](#recipientCountryDescription)|A description of the recipient country.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[recipientCountryId](#recipientCountryId)|A country that will benefit from this transaction.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[recipientOrganizationId](#recipientOrganizationId)|The organization receiving the money from the transaction.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[recipientRegionDescription](#recipientRegionDescription)|A description of the recipient region.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[recipientRegionId](#recipientRegionId)|A region that will benefit from this transaction.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[tiedStatusId](#tiedStatusId)|Whether the aid is untied, tied, or partially tied.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[transactionType](#transactionType)|The type of transaction.|<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|
|[transactionType_display](#transactionType_display)||<a href="Disbursement.md" target="_blank">nonProfit/Disbursement</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#disbursementId name="disbursementId">disbursementId</a>

Unique identifier for entity instances  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disbursement</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_disbursementid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Disbursement  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Disbursement</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Disbursement  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Disbursement</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#adjustmentComment name="adjustmentComment">adjustmentComment</a>

Any notes or details about the adjustment that the user may have optionally entered.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjustment Comment</td></tr><tr><td>description</td><td>Any notes or details about the adjustment that the user may have optionally entered.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_adjustmentcomment</td></tr></table>

### <a href=#adjustmentReason name="adjustmentReason">adjustmentReason</a>

First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjustment Reason</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_adjustmentreason</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Adjustment Reason Option</td><td>844060000</td></tr><tr><td>en</td><td>Adjustment Reason Option</td><td>844060000</td></tr></table></td></tr></table>

### <a href=#adjustmentReason_display name="adjustmentReason_display">adjustmentReason_display</a>

First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#adjustmentType name="adjustmentType">adjustmentType</a>

First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjustment Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_adjustmenttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Adjustment Type Option</td><td>844060000</td></tr><tr><td>en</td><td>Adjustment Type Option</td><td>844060000</td></tr></table></td></tr></table>

### <a href=#adjustmentType_display name="adjustmentType_display">adjustmentType_display</a>

First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#adjustsOriginalTransactionId name="adjustsOriginalTransactionId">adjustsOriginalTransactionId</a>

Adjusts Original Transaction  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjusts Original Transaction</td></tr><tr><td>description</td><td>Adjusts Original Transaction</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_adjustsoriginaltransactionid</td></tr></table>

### <a href=#amouont name="amouont">amouont</a>

The amount of the Disbursement.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount</td></tr><tr><td>description</td><td>The amount of the Disbursement.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amouont</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amouontBase name="amouontBase">amouontBase</a>

Value of the Amount in base currency.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base)</td></tr><tr><td>description</td><td>Value of the Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_amouont_base</td></tr></table>

### <a href=#awardId name="awardId">awardId</a>

Award  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Award</td></tr><tr><td>description</td><td>Award</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_awardid</td></tr></table>

### <a href=#bookDate name="bookDate">bookDate</a>

Book Date  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Book Date</td></tr><tr><td>description</td><td>Book Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_bookdate</td></tr></table>

### <a href=#comment name="comment">comment</a>

Comments about the Disbursement.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Comment</td></tr><tr><td>description</td><td>Comments about the Disbursement.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_comment</td></tr></table>

### <a href=#description name="description">description</a>

Description of the Disbursement.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the Disbursement.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_description</td></tr></table>

### <a href=#isAdjusted name="isAdjusted">isAdjusted</a>

Is Adjusted  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Adjusted</td></tr><tr><td>description</td><td>Is Adjusted</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_isadjusted</td></tr></table>

### <a href=#postedDate name="postedDate">postedDate</a>

The date the Disbursement was posted to the GL  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Posted Date</td></tr><tr><td>description</td><td>The date the Disbursement was posted to the GL</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_posteddate</td></tr></table>

### <a href=#recipientAccountId name="recipientAccountId">recipientAccountId</a>

Recipient Account  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Account</td></tr><tr><td>description</td><td>Recipient Account</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_recipientaccountid</td></tr></table>

### <a href=#recipientContactId name="recipientContactId">recipientContactId</a>

Recipient Contact  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Contact</td></tr><tr><td>description</td><td>Recipient Contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_recipientcontactid</td></tr></table>

### <a href=#requestDate name="requestDate">requestDate</a>

The date the Disbursement was requested.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Request Date</td></tr><tr><td>description</td><td>The date the Disbursement was requested.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_requestdate</td></tr></table>

### <a href=#scheduledDisbursementDate name="scheduledDisbursementDate">scheduledDisbursementDate</a>

The date the Disbursement is scheduled to be sent.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Disbursement Date</td></tr><tr><td>description</td><td>The date the Disbursement is scheduled to be sent.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_scheduleddisbursementdate</td></tr></table>

### <a href=#sentDate name="sentDate">sentDate</a>

The date the Disbursement was sent.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sent Date</td></tr><tr><td>description</td><td>The date the Disbursement was sent.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_sentdate</td></tr></table>

### <a href=#status name="status">status</a>

Status of the Disbursement.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Disbursement.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_status</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Scheduled</td><td>844060000</td></tr><tr><td>en</td><td>Check Request</td><td>844060001</td></tr><tr><td>en</td><td>Paid</td><td>844060002</td></tr><tr><td>en</td><td>Cancelled</td><td>844060003</td></tr><tr><td>en</td><td>Scheduled</td><td>844060000</td></tr><tr><td>en</td><td>Check Request</td><td>844060001</td></tr><tr><td>en</td><td>Paid</td><td>844060002</td></tr><tr><td>en</td><td>Cancelled</td><td>844060003</td></tr></table></td></tr></table>

### <a href=#status_display name="status_display">status_display</a>

First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#type name="type">type</a>

The type of Disbursement.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>The type of Disbursement.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_type</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Check</td><td>844060000</td></tr><tr><td>en</td><td>Wire Transfer</td><td>844060001</td></tr><tr><td>en</td><td>Credit Card</td><td>844060002</td></tr><tr><td>en</td><td>Other</td><td>844060003</td></tr><tr><td>en</td><td>Check</td><td>844060000</td></tr><tr><td>en</td><td>Wire Transfer</td><td>844060001</td></tr><tr><td>en</td><td>Credit Card</td><td>844060002</td></tr><tr><td>en</td><td>Other</td><td>844060003</td></tr></table></td></tr></table>

### <a href=#type_display name="type_display">type_display</a>

First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#budgetType name="budgetType">budgetType</a>

OECD DAC classification used to determine the character of resource flows (bilateral or multilateral)  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget Type</td></tr><tr><td>description</td><td>OECD DAC classification used to determine the character of resource flows (bilateral or multilateral)</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_budgettype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Original</td><td>453490001</td></tr><tr><td>en</td><td>Revised</td><td>453490002</td></tr></table></td></tr></table>

### <a href=#budgetType_display name="budgetType_display">budgetType_display</a>

First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#currencyValueDate name="currencyValueDate">currencyValueDate</a>

Date for the currency value  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency Value Date</td></tr><tr><td>description</td><td>Date for the currency value</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_currencyvaluedate</td></tr></table>

### <a href=#disbursementChannelId name="disbursementChannelId">disbursementChannelId</a>

The channel through which the funds will flow for this transaction.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disbursement Channel</td></tr><tr><td>description</td><td>The channel through which the funds will flow for this transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_disbursementchannelid</td></tr></table>

### <a href=#financeTypeId name="financeTypeId">financeTypeId</a>

The type of finance (e.g. grant, loan, debt relief, etc.).  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Finance Type</td></tr><tr><td>description</td><td>The type of finance (e.g. grant, loan, debt relief, etc.).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_financetypeid</td></tr></table>

### <a href=#flowTypeId name="flowTypeId">flowTypeId</a>

Whether the transaction is funded by Official Development Assistance (ODA), Other Official Flows (OOF), etc.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Flow Type</td></tr><tr><td>description</td><td>Whether the transaction is funded by Official Development Assistance (ODA), Other Official Flows (OOF), etc.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_flowtypeid</td></tr></table>

### <a href=#humanitarian name="humanitarian">humanitarian</a>

Indicates that this transaction relates entirely or partially to humanitarian aid.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Humanitarian</td></tr><tr><td>description</td><td>Indicates that this transaction relates entirely or partially to humanitarian aid.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_humanitarian</td></tr></table>

### <a href=#periodEnd name="periodEnd">periodEnd</a>

Date for the period end  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period End</td></tr><tr><td>description</td><td>Date for the period end</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_periodend</td></tr></table>

### <a href=#periodStart name="periodStart">periodStart</a>

Date for the period start  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period Start</td></tr><tr><td>description</td><td>Date for the period start</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_periodstart</td></tr></table>

### <a href=#providerActivityIdentifier name="providerActivityIdentifier">providerActivityIdentifier</a>

If incoming funds are being provided from the budget of another activity, record the activity's unique identifier.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Provider Activity Identifier</td></tr><tr><td>description</td><td>If incoming funds are being provided from the budget of another activity, record the activity's unique identifier.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_provideractivityidentifier</td></tr></table>

### <a href=#providerOrganizationId name="providerOrganizationId">providerOrganizationId</a>

The organization from which the transaction originated.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Provider Organization</td></tr><tr><td>description</td><td>The organization from which the transaction originated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_providerorganizationid</td></tr></table>

### <a href=#recipientActivityIdentifier name="recipientActivityIdentifier">recipientActivityIdentifier</a>

If outgoing funds are being provided to another activity, record the activity's unique identifier.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Activity Identifier</td></tr><tr><td>description</td><td>If outgoing funds are being provided to another activity, record the activity's unique identifier.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientactivityidentifier</td></tr></table>

### <a href=#recipientCountryDescription name="recipientCountryDescription">recipientCountryDescription</a>

A description of the recipient country.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Country Description</td></tr><tr><td>description</td><td>A description of the recipient country.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientcountrydescription</td></tr></table>

### <a href=#recipientCountryId name="recipientCountryId">recipientCountryId</a>

A country that will benefit from this transaction.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Country</td></tr><tr><td>description</td><td>A country that will benefit from this transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientcountryid</td></tr></table>

### <a href=#recipientOrganizationId name="recipientOrganizationId">recipientOrganizationId</a>

The organization receiving the money from the transaction.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Organization</td></tr><tr><td>description</td><td>The organization receiving the money from the transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientorganizationid</td></tr></table>

### <a href=#recipientRegionDescription name="recipientRegionDescription">recipientRegionDescription</a>

A description of the recipient region.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Region Description</td></tr><tr><td>description</td><td>A description of the recipient region.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientregiondescription</td></tr></table>

### <a href=#recipientRegionId name="recipientRegionId">recipientRegionId</a>

A region that will benefit from this transaction.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Region</td></tr><tr><td>description</td><td>A region that will benefit from this transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientregionid</td></tr></table>

### <a href=#tiedStatusId name="tiedStatusId">tiedStatusId</a>

Whether the aid is untied, tied, or partially tied.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tied Status</td></tr><tr><td>description</td><td>Whether the aid is untied, tied, or partially tied.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_tiedstatusid</td></tr></table>

### <a href=#transactionType name="transactionType">transactionType</a>

The type of transaction.  
First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Type</td></tr><tr><td>description</td><td>The type of transaction.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_transactiontype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Disbursement</td><td>453490002</td></tr><tr><td>en</td><td>Outgoing Commitment</td><td>453490000</td></tr><tr><td>en</td><td>Outgoing Pledge</td><td>453490001</td></tr></table></td></tr></table>

### <a href=#transactionType_display name="transactionType_display">transactionType_display</a>

First included in: nonProfit/Disbursement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
