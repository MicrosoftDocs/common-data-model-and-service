---
title: Expenditure - Common Data Model | Microsoft Docs
description: An Expenditure represents an amount of money spent by an Organization or Delivery Framework.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Expenditure

An Expenditure represents an amount of money spent by an Organization or Delivery Framework.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/Expenditure.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/nonProfit/Expenditure  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[expenditureId](#expenditureId)|Unique identifier for entity instances|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[stateCode](#stateCode)|Status of the Expenditure|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[stateCode_display](#stateCode_display)||<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[statusCode](#statusCode)|Reason for the status of the Expenditure|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[statusCode_display](#statusCode_display)||<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[name](#name)|The name of the custom entity.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[currencyValueDate](#currencyValueDate)||<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[deliveryFrameworkId](#deliveryFrameworkId)|Unique identifier for Delivery Framework associated with Expenditure.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[description](#description)|A description of the transaction.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[disbursementChannelId](#disbursementChannelId)|The channel through which the funds will flow for this transaction.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[endDate](#endDate)||<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[financeTypeId](#financeTypeId)|The type of finance (e.g. grant, loan, debt relief, etc.).|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[flowTypeId](#flowTypeId)|Whether the transaction is funded by Official Development Assistance (ODA), Other Official Flows (OOF), etc.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[humanitarian](#humanitarian)|Indicates that this transaction relates entirely or partially to humanitarian aid.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[organizationId](#organizationId)|Unique identifier for Account associated with Expenditure.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[providerActivityIdentifier](#providerActivityIdentifier)|If incoming funds are being provided from the budget of another activity, record the activity's unique identifier.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[providerOrganizationId](#providerOrganizationId)|The organization from which the transaction originated.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[recipientActivityIdentifier](#recipientActivityIdentifier)|If outgoing funds are being provided to another activity, record the activity's unique identifier.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[recipientCountryDescription](#recipientCountryDescription)|A description of the recipient country.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[recipientCountryId](#recipientCountryId)|A country that will benefit from this transaction.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[recipientOrganizationId](#recipientOrganizationId)|The organization receiving the money from the transaction.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[recipientRegionDescription](#recipientRegionDescription)|A description of the recipient region.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[recipientRegionId](#recipientRegionId)|A region that will benefit from this transaction.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[relatedTo](#relatedTo)|Indicates the entity to which the transaction is related.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[relatedTo_display](#relatedTo_display)||<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[startDate](#startDate)||<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[tiedStatusId](#tiedStatusId)|Whether the aid is untied, tied, or partially tied.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[totalExpenditure](#totalExpenditure)||<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[msiatiTotalexpenditureBase](#msiatiTotalexpenditureBase)|Value of the Total Expenditure in base currency.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[transactionType](#transactionType)|The type of transaction.|<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|
|[transactionType_display](#transactionType_display)||<a href="Expenditure.md" target="_blank">nonProfit/Expenditure</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#expenditureId name="expenditureId">expenditureId</a>

Unique identifier for entity instances  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expenditure</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msiati_expenditureid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Expenditure  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Expenditure</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Expenditure  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Expenditure</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#name name="name">name</a>

The name of the custom entity.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_name</td></tr></table>

### <a href=#currencyValueDate name="currencyValueDate">currencyValueDate</a>

First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency Value Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_currencyvaluedate</td></tr></table>

### <a href=#deliveryFrameworkId name="deliveryFrameworkId">deliveryFrameworkId</a>

Unique identifier for Delivery Framework associated with Expenditure.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery Framework</td></tr><tr><td>description</td><td>Unique identifier for Delivery Framework associated with Expenditure.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_deliveryframeworkid</td></tr></table>

### <a href=#description name="description">description</a>

A description of the transaction.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>A description of the transaction.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_description</td></tr></table>

### <a href=#disbursementChannelId name="disbursementChannelId">disbursementChannelId</a>

The channel through which the funds will flow for this transaction.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disbursement Channel</td></tr><tr><td>description</td><td>The channel through which the funds will flow for this transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_disbursementchannelid</td></tr></table>

### <a href=#endDate name="endDate">endDate</a>

First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_enddate</td></tr></table>

### <a href=#financeTypeId name="financeTypeId">financeTypeId</a>

The type of finance (e.g. grant, loan, debt relief, etc.).  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Finance Type</td></tr><tr><td>description</td><td>The type of finance (e.g. grant, loan, debt relief, etc.).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_financetypeid</td></tr></table>

### <a href=#flowTypeId name="flowTypeId">flowTypeId</a>

Whether the transaction is funded by Official Development Assistance (ODA), Other Official Flows (OOF), etc.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Flow Type</td></tr><tr><td>description</td><td>Whether the transaction is funded by Official Development Assistance (ODA), Other Official Flows (OOF), etc.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_flowtypeid</td></tr></table>

### <a href=#humanitarian name="humanitarian">humanitarian</a>

Indicates that this transaction relates entirely or partially to humanitarian aid.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Humanitarian</td></tr><tr><td>description</td><td>Indicates that this transaction relates entirely or partially to humanitarian aid.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_humanitarian</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for Account associated with Expenditure.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>Unique identifier for Account associated with Expenditure.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_organizationid</td></tr></table>

### <a href=#providerActivityIdentifier name="providerActivityIdentifier">providerActivityIdentifier</a>

If incoming funds are being provided from the budget of another activity, record the activity's unique identifier.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Provider Activity Identifier</td></tr><tr><td>description</td><td>If incoming funds are being provided from the budget of another activity, record the activity's unique identifier.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_provideractivityidentifier</td></tr></table>

### <a href=#providerOrganizationId name="providerOrganizationId">providerOrganizationId</a>

The organization from which the transaction originated.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Provider Organization</td></tr><tr><td>description</td><td>The organization from which the transaction originated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_providerorganizationid</td></tr></table>

### <a href=#recipientActivityIdentifier name="recipientActivityIdentifier">recipientActivityIdentifier</a>

If outgoing funds are being provided to another activity, record the activity's unique identifier.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Activity Identifier</td></tr><tr><td>description</td><td>If outgoing funds are being provided to another activity, record the activity's unique identifier.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientactivityidentifier</td></tr></table>

### <a href=#recipientCountryDescription name="recipientCountryDescription">recipientCountryDescription</a>

A description of the recipient country.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Country Description</td></tr><tr><td>description</td><td>A description of the recipient country.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientcountrydescription</td></tr></table>

### <a href=#recipientCountryId name="recipientCountryId">recipientCountryId</a>

A country that will benefit from this transaction.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Country</td></tr><tr><td>description</td><td>A country that will benefit from this transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientcountryid</td></tr></table>

### <a href=#recipientOrganizationId name="recipientOrganizationId">recipientOrganizationId</a>

The organization receiving the money from the transaction.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Organization</td></tr><tr><td>description</td><td>The organization receiving the money from the transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientorganizationid</td></tr></table>

### <a href=#recipientRegionDescription name="recipientRegionDescription">recipientRegionDescription</a>

A description of the recipient region.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Region Description</td></tr><tr><td>description</td><td>A description of the recipient region.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientregiondescription</td></tr></table>

### <a href=#recipientRegionId name="recipientRegionId">recipientRegionId</a>

A region that will benefit from this transaction.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient Region</td></tr><tr><td>description</td><td>A region that will benefit from this transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_recipientregionid</td></tr></table>

### <a href=#relatedTo name="relatedTo">relatedTo</a>

Indicates the entity to which the transaction is related.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Related To</td></tr><tr><td>description</td><td>Indicates the entity to which the transaction is related.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_relatedto</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Account</td><td>453490001</td></tr><tr><td>en</td><td>Delivery Framework</td><td>453490000</td></tr></table></td></tr></table>

### <a href=#relatedTo_display name="relatedTo_display">relatedTo_display</a>

First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#startDate name="startDate">startDate</a>

First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_startdate</td></tr></table>

### <a href=#tiedStatusId name="tiedStatusId">tiedStatusId</a>

Whether the aid is untied, tied, or partially tied.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tied Status</td></tr><tr><td>description</td><td>Whether the aid is untied, tied, or partially tied.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_tiedstatusid</td></tr></table>

### <a href=#totalExpenditure name="totalExpenditure">totalExpenditure</a>

First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Expenditure</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_totalexpenditure</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#msiatiTotalexpenditureBase name="msiatiTotalexpenditureBase">msiatiTotalexpenditureBase</a>

Value of the Total Expenditure in base currency.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Expenditure (Base)</td></tr><tr><td>description</td><td>Value of the Total Expenditure in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_totalexpenditure_base</td></tr></table>

### <a href=#transactionType name="transactionType">transactionType</a>

The type of transaction.  
First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Type</td></tr><tr><td>description</td><td>The type of transaction.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msiati_transactiontype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Expenditure</td><td>453490000</td></tr><tr><td>en</td><td>Interest Payment</td><td>453490001</td></tr><tr><td>en</td><td>Loan Repayment</td><td>453490002</td></tr><tr><td>en</td><td>Purchase of Equity</td><td>453490004</td></tr><tr><td>en</td><td>Reimbursement</td><td>453490003</td></tr></table></td></tr></table>

### <a href=#transactionType_display name="transactionType_display">transactionType_display</a>

First included in: nonProfit/Expenditure (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
