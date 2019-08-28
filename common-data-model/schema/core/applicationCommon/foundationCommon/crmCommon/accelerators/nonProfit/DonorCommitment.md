---
title: DonorCommitment - Common Data Model | Microsoft Docs
description: This describes the DonorCommitment entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Donor Commitment

Donor commitments represent the actual or prospective agreement between a donor and an organization for the donor to make a gift to the organization.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/DonorCommitment.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/DonorCommitment  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[ownerId](#ownerId)|Owner Id|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[donorCommitmentId](#donorCommitmentId)|Unique identifier for entity instances|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[stateCode](#stateCode)|Status of the Donor Commitment|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[stateCode_display](#stateCode_display)||<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[statusCode](#statusCode)|Reason for the status of the Donor Commitment|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[statusCode_display](#statusCode_display)||<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[name](#name)||<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[anonymity](#anonymity)||<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[anonymity_display](#anonymity_display)||<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[bookDate](#bookDate)|The date on which revenue will be recognized|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[commitmentCampaignId](#commitmentCampaignId)|Campaign|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[commitmentDefaultDesignationId](#commitmentDefaultDesignationId)|Default Designation|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[commitmentDate](#commitmentDate)|This is the date that the donor made the commitment, not necessarily the date that the commitment was entered into the system.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[commitmentType](#commitmentType)||<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[commitmentType_display](#commitmentType_display)||<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[dataEntryReference](#dataEntryReference)||<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[dataEntrySource](#dataEntrySource)||<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[dataEntrySource_display](#dataEntrySource_display)||<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[donorCommitmentPlannedGivingId](#donorCommitmentPlannedGivingId)|Planned Giving|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[expectedByDate](#expectedByDate)||<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[isBookable](#isBookable)||<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[nextPaymentAmount](#nextPaymentAmount)||<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[nextPaymentAmountBase](#nextPaymentAmountBase)|Value of the Next Payment Amount in base currency.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[nextPaymentDate](#nextPaymentDate)||<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[opportunityId](#opportunityId)|Unique identifier for Opportunity associated with Donor Commitment.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[pledgedByContactId](#pledgedByContactId)|Pledged By Contact|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[pledgedOnAccountId](#pledgedOnAccountId)|Pledged On Account|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[receivedDate](#receivedDate)||<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[totalAmount](#totalAmount)||<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[totalAmountBase](#totalAmountBase)|Value of the Total Amount in base currency.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[currencyValueDate](#currencyValueDate)|The date on which the transaction was made or agreed.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[description](#description)|A description of the transaction.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[disbursementChannelId](#disbursementChannelId)|The channel through which the funds will flow for this transaction.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[financeTypeId](#financeTypeId)|The type of finance (e.g. grant, loan, debt relief, etc.).|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[flowTypeId](#flowTypeId)|Whether the transaction is funded by Official Development Assistance (ODA), Other Official Flows (OOF), etc.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[humanitarian](#humanitarian)|Indicates that this transaction relates entirely or partially to humanitarian aid.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[providerActivityIdentifier](#providerActivityIdentifier)|If incoming funds are being provided from the budget of another activity, record the activity's unique identifier.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[providerOrganizationId](#providerOrganizationId)|The organization from which the transaction originated.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[recipientActivityIdentifier](#recipientActivityIdentifier)|If outgoing funds are being provided to another activity, record the activity's unique identifier.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[recipientCountryDescription](#recipientCountryDescription)|A description of the recipient country.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[recipientCountryId](#recipientCountryId)|A country that will benefit from this transaction.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[recipientOrganizationId](#recipientOrganizationId)|The organization receiving the money from the transaction.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[recipientRegionDescription](#recipientRegionDescription)|A description of the recipient region.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[recipientRegionId](#recipientRegionId)|A region that will benefit from this transaction.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[tiedStatusId](#tiedStatusId)|Whether the aid is untied, tied, or partially tied.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[transactionType](#transactionType)|The type of transaction.|<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|
|[transactionType_display](#transactionType_display)||<a href="DonorCommitment.md" target="_blank">nonProfit/DonorCommitment</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#donorCommitmentId name="donorCommitmentId">donorCommitmentId</a>

Unique identifier for entity instances  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Donor Commitment</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msnfp_donorcommitmentid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Donor Commitment  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Donor Commitment</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Donor Commitment  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Donor Commitment</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_name</td></tr></table>

### <a href=#anonymity name="anonymity">anonymity</a>

First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Anonymity</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_anonymity</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Yes</td><td>100000000</td></tr><tr><td>en</td><td>No</td><td>100000001</td></tr></table></td></tr></table>

### <a href=#anonymity_display name="anonymity_display">anonymity_display</a>

First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#bookDate name="bookDate">bookDate</a>

The date on which revenue will be recognized  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Book Date</td></tr><tr><td>description</td><td>The date on which revenue will be recognized</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_bookdate</td></tr></table>

### <a href=#commitmentCampaignId name="commitmentCampaignId">commitmentCampaignId</a>

Campaign  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Campaign</td></tr><tr><td>description</td><td>Campaign</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_commitment_campaignid</td></tr></table>

### <a href=#commitmentDefaultDesignationId name="commitmentDefaultDesignationId">commitmentDefaultDesignationId</a>

Default Designation  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Designation</td></tr><tr><td>description</td><td>Default Designation</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_commitment_defaultdesignationid</td></tr></table>

### <a href=#commitmentDate name="commitmentDate">commitmentDate</a>

This is the date that the donor made the commitment, not necessarily the date that the commitment was entered into the system.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commitment Date</td></tr><tr><td>description</td><td>This is the date that the donor made the commitment, not necessarily the date that the commitment was entered into the system.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_commitmentdate</td></tr></table>

### <a href=#commitmentType name="commitmentType">commitmentType</a>

First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commitment Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_commitmenttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Sustainer pledge</td><td>100000000</td></tr><tr><td>en</td><td>Installment pledge</td><td>100000001</td></tr><tr><td>en</td><td>In-kind pledge</td><td>100000002</td></tr></table></td></tr></table>

### <a href=#commitmentType_display name="commitmentType_display">commitmentType_display</a>

First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#dataEntryReference name="dataEntryReference">dataEntryReference</a>

First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Data Entry Reference</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_dataentryreference</td></tr></table>

### <a href=#dataEntrySource name="dataEntrySource">dataEntrySource</a>

First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Data Entry Source</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_dataentrysource</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>DataEntryType</td><td>100000000</td></tr></table></td></tr></table>

### <a href=#dataEntrySource_display name="dataEntrySource_display">dataEntrySource_display</a>

First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#donorCommitmentPlannedGivingId name="donorCommitmentPlannedGivingId">donorCommitmentPlannedGivingId</a>

Planned Giving  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned Giving</td></tr><tr><td>description</td><td>Planned Giving</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_donorcommitment_plannedgivingid</td></tr></table>

### <a href=#expectedByDate name="expectedByDate">expectedByDate</a>

First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expected By Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_expectedbydate</td></tr></table>

### <a href=#isBookable name="isBookable">isBookable</a>

First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Bookable</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_isbookable</td></tr></table>

### <a href=#nextPaymentAmount name="nextPaymentAmount">nextPaymentAmount</a>

First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Next Payment Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_nextpaymentamount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#nextPaymentAmountBase name="nextPaymentAmountBase">nextPaymentAmountBase</a>

Value of the Next Payment Amount in base currency.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Next Payment Amount (Base)</td></tr><tr><td>description</td><td>Value of the Next Payment Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_nextpaymentamount_base</td></tr></table>

### <a href=#nextPaymentDate name="nextPaymentDate">nextPaymentDate</a>

First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Next Payment Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_nextpaymentdate</td></tr></table>

### <a href=#opportunityId name="opportunityId">opportunityId</a>

Unique identifier for Opportunity associated with Donor Commitment.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Opportunity</td></tr><tr><td>description</td><td>Unique identifier for Opportunity associated with Donor Commitment.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_opportunityid</td></tr></table>

### <a href=#pledgedByContactId name="pledgedByContactId">pledgedByContactId</a>

Pledged By Contact  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pledged By Contact</td></tr><tr><td>description</td><td>Pledged By Contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_pledgedbycontactid</td></tr></table>

### <a href=#pledgedOnAccountId name="pledgedOnAccountId">pledgedOnAccountId</a>

Pledged On Account  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pledged On Account</td></tr><tr><td>description</td><td>Pledged On Account</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_pledgedonaccountid</td></tr></table>

### <a href=#receivedDate name="receivedDate">receivedDate</a>

First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Received Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_receiveddate</td></tr></table>

### <a href=#totalAmount name="totalAmount">totalAmount</a>

First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_totalamount</td></tr></table>

### <a href=#totalAmountBase name="totalAmountBase">totalAmountBase</a>

Value of the Total Amount in base currency.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Amount (Base)</td></tr><tr><td>description</td><td>Value of the Total Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msnfp_totalamount_base</td></tr></table>

### <a href=#currencyValueDate name="currencyValueDate">currencyValueDate</a>

The date on which the transaction was made or agreed.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency Value Date</td></tr><tr><td>description</td><td>The date on which the transaction was made or agreed.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_currencyvaluedate</td></tr></table>

### <a href=#description name="description">description</a>

A description of the transaction.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>A description of the transaction.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_description</td></tr></table>

### <a href=#disbursementChannelId name="disbursementChannelId">disbursementChannelId</a>

The channel through which the funds will flow for this transaction.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disbursement Channel</td></tr><tr><td>description</td><td>The channel through which the funds will flow for this transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_disbursementchannelid</td></tr></table>

### <a href=#financeTypeId name="financeTypeId">financeTypeId</a>

The type of finance (e.g. grant, loan, debt relief, etc.).  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Finance Type</td></tr><tr><td>description</td><td>The type of finance (e.g. grant, loan, debt relief, etc.).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_financetypeid</td></tr></table>

### <a href=#flowTypeId name="flowTypeId">flowTypeId</a>

Whether the transaction is funded by Official Development Assistance (ODA), Other Official Flows (OOF), etc.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Flow Type</td></tr><tr><td>description</td><td>Whether the transaction is funded by Official Development Assistance (ODA), Other Official Flows (OOF), etc.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_flowtypeid</td></tr></table>

### <a href=#humanitarian name="humanitarian">humanitarian</a>

Indicates that this transaction relates entirely or partially to humanitarian aid.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Humanitarian</td></tr><tr><td>description</td><td>Indicates that this transaction relates entirely or partially to humanitarian aid.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_humanitarian</td></tr></table>

### <a href=#providerActivityIdentifier name="providerActivityIdentifier">providerActivityIdentifier</a>

If incoming funds are being provided from the budget of another activity, record the activity's unique identifier.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Provider Activity Identifier</td></tr><tr><td>description</td><td>If incoming funds are being provided from the budget of another activity, record the activity's unique identifier.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_provideractivityidentifier</td></tr></table>

### <a href=#providerOrganizationId name="providerOrganizationId">providerOrganizationId</a>

The organization from which the transaction originated.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Provider Organization</td></tr><tr><td>description</td><td>The organization from which the transaction originated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_providerorganizationid</td></tr></table>

### <a href=#recipientActivityIdentifier name="recipientActivityIdentifier">recipientActivityIdentifier</a>

If outgoing funds are being provided to another activity, record the activity's unique identifier.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Activity Identifier</td></tr><tr><td>description</td><td>If outgoing funds are being provided to another activity, record the activity's unique identifier.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientactivityidentifier</td></tr></table>

### <a href=#recipientCountryDescription name="recipientCountryDescription">recipientCountryDescription</a>

A description of the recipient country.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Country Description</td></tr><tr><td>description</td><td>A description of the recipient country.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientcountrydescription</td></tr></table>

### <a href=#recipientCountryId name="recipientCountryId">recipientCountryId</a>

A country that will benefit from this transaction.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Country</td></tr><tr><td>description</td><td>A country that will benefit from this transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientcountryid</td></tr></table>

### <a href=#recipientOrganizationId name="recipientOrganizationId">recipientOrganizationId</a>

The organization receiving the money from the transaction.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Organization</td></tr><tr><td>description</td><td>The organization receiving the money from the transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientorganizationid</td></tr></table>

### <a href=#recipientRegionDescription name="recipientRegionDescription">recipientRegionDescription</a>

A description of the recipient region.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Region Description</td></tr><tr><td>description</td><td>A description of the recipient region.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientregiondescription</td></tr></table>

### <a href=#recipientRegionId name="recipientRegionId">recipientRegionId</a>

A region that will benefit from this transaction.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Region</td></tr><tr><td>description</td><td>A region that will benefit from this transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientregionid</td></tr></table>

### <a href=#tiedStatusId name="tiedStatusId">tiedStatusId</a>

Whether the aid is untied, tied, or partially tied.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tied Status</td></tr><tr><td>description</td><td>Whether the aid is untied, tied, or partially tied.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_tiedstatusid</td></tr></table>

### <a href=#transactionType name="transactionType">transactionType</a>

The type of transaction.  
First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Type</td></tr><tr><td>description</td><td>The type of transaction.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_transactiontype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Incoming Commitment</td><td>453490000</td></tr><tr><td>en</td><td>Incomming Pledge</td><td>453490001</td></tr></table></td></tr></table>

### <a href=#transactionType_display name="transactionType_display">transactionType_display</a>

First included in: nonProfit/DonorCommitment (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
