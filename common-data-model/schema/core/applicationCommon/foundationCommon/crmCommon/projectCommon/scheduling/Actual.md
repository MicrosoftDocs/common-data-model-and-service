---
title: Actual - Common Data Model | Microsoft Docs
description: This describes the Actual entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Actual

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/scheduling/Actual.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/scheduling/Actual  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[actualId](#actualId)|Unique identifier for entity instances|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[stateCode](#stateCode)|Status of the Actual|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[stateCode_display](#stateCode_display)||<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[statusCode](#statusCode)|Reason for the status of the Actual|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[statusCode_display](#statusCode_display)||<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[description](#description)|Type the record description.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[accountCustomer](#accountCustomer)|Select the customer.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[accountingDate](#accountingDate)||<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[accountVendor](#accountVendor)||<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[adjustmentStatus](#adjustmentStatus)|Shows the adjustment status ID of the transaction.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[adjustmentStatus_display](#adjustmentStatus_display)||<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[amount](#amount)|Enter the amount in transaction currency.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Shows the currency associated with the entity.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[amountBase](#amountBase)|Enter the value of the amount in the base (organization) currency.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[amountMethod](#amountMethod)|Select the method by which the amount was computed.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[amountMethod_display](#amountMethod_display)||<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[basisAmount](#basisAmount)|Enter the cost amount of the sales transaction in the transaction currency.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[basisAmountBase](#basisAmountBase)|Enter the cost amount of the sales transaction in the base (organization) currency.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[basisPrice](#basisPrice)|Enter the cost price of the sales transaction in transaction currency.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[basisPriceBase](#basisPriceBase)|Enter the cost price of the sales transaction in base (organization) currency.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[basisQuantity](#basisQuantity)|Enter the cost quantity of the sales transaction in the base (organization) currency.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[billingStatus](#billingStatus)|Select the billing status ID.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[billingStatus_display](#billingStatus_display)||<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[billingType](#billingType)|Select the billing type ID.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[billingType_display](#billingType_display)||<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[bookableResource](#bookableResource)|Shows the bookable resource for which the actual is recorded.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[contactCustomer](#contactCustomer)|Select the customer contact.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[contactVendor](#contactVendor)||<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[customerType](#customerType)|Select the customer type ID.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[customerType_display](#customerType_display)||<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[documentDate](#documentDate)|Enter the transaction date of the business event.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[endDateTime](#endDateTime)|Enter the end date and time for this transaction.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[exchangeRateDate](#exchangeRateDate)|Enter the date of the exchange rate used for this transaction.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[externalDescription](#externalDescription)|The external description of the business transaction.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[externalReferenceDate](#externalReferenceDate)|Stores a date from an external system, such as a journal entry voucher date from an ERP system|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[externalReferenceID](#externalReferenceID)|Stores an ID from an external system, such as the journal entry voucher number from an ERP system.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[invoice](#invoice)|The unique identifier of an invoice.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[isJournalized](#isJournalized)||<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[percent](#percent)|Enter the percent.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[price](#price)|Enter the price in the transaction currency.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[priceBase](#priceBase)|Enter the price in the base (organization) currency.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[priceList](#priceList)|Select the price list.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[product](#product)|Select the product ID.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[quantity](#quantity)|Enter the quantity.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[salesContract](#salesContract)|Select the project contract.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[salesContractLine](#salesContractLine)|(Deprecated) Type the project contract line.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[startDateTime](#startDateTime)|Enter the start date and time.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[transactionClassification](#transactionClassification)|Shows the transaction classification of this transaction.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[transactionClassification_display](#transactionClassification_display)||<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[transactionTypeCode](#transactionTypeCode)|Shows the transaction type of this transaction.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[transactionTypeCode_display](#transactionTypeCode_display)||<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[unit](#unit)|Select the unit of measure.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[unitSchedule](#unitSchedule)|Select the unit schedule.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[vendorType](#vendorType)||<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[vendorType_display](#vendorType_display)||<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[contractingUnit](#contractingUnit)|Select the organizational unit ID for the contract.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[project](#project)|Select the project ID.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[resourceCategory](#resourceCategory)|Select the role ID of the resource performing the work.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[resourceOrganizationalUnitId](#resourceOrganizationalUnitId)|Organizational unit at the time the actual was registered of the resource who performed the work.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[salesContractLineId](#salesContractLineId)|Unique identifier for Project Contract Line associated with Actual.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[task](#task)|Select the task.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|
|[transactionCategory](#transactionCategory)|Select the transaction category.|<a href="Actual.md" target="_blank">scheduling/Actual</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#actualId name="actualId">actualId</a>

Unique identifier for entity instances  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_actualid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Actual  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Actual</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Actual  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Actual</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

Type the record description.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type the record description.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_description</td></tr></table>

### <a href=#accountCustomer name="accountCustomer">accountCustomer</a>

Select the customer.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer ID</td></tr><tr><td>description</td><td>Select the customer.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_accountcustomer</td></tr></table>

### <a href=#accountingDate name="accountingDate">accountingDate</a>

First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accounting Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_accountingdate</td></tr></table>

### <a href=#accountVendor name="accountVendor">accountVendor</a>

First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_accountvendor</td></tr></table>

### <a href=#adjustmentStatus name="adjustmentStatus">adjustmentStatus</a>

Shows the adjustment status ID of the transaction.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjustment Status ID</td></tr><tr><td>description</td><td>Shows the adjustment status ID of the transaction.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_adjustmentstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>In Process</td><td>192350000</td></tr><tr><td>en</td><td>Adjusted</td><td>192350001</td></tr><tr><td>en</td><td>Unadjustable</td><td>192350002</td></tr><tr><td>en</td><td>In Process</td><td>192350000</td></tr><tr><td>en</td><td>Adjusted</td><td>192350001</td></tr><tr><td>en</td><td>Unadjustable</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#adjustmentStatus_display name="adjustmentStatus_display">adjustmentStatus_display</a>

First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#amount name="amount">amount</a>

Enter the amount in transaction currency.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount</td></tr><tr><td>description</td><td>Enter the amount in transaction currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Shows the currency associated with the entity.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Shows the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amountBase name="amountBase">amountBase</a>

Enter the value of the amount in the base (organization) currency.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base currency)</td></tr><tr><td>description</td><td>Enter the value of the amount in the base (organization) currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount_base</td></tr></table>

### <a href=#amountMethod name="amountMethod">amountMethod</a>

Select the method by which the amount was computed.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Method ID</td></tr><tr><td>description</td><td>Select the method by which the amount was computed.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amountmethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Multiply Quantity By Price</td><td>192350000</td></tr><tr><td>en</td><td>Fixed Price</td><td>192350001</td></tr><tr><td>en</td><td>Multiply Basis Quantity By Price</td><td>192350002</td></tr><tr><td>en</td><td>Multiply Basis Amount By Percent</td><td>192350003</td></tr><tr><td>en</td><td>Multiply Quantity By Price</td><td>192350000</td></tr><tr><td>en</td><td>Fixed Price</td><td>192350001</td></tr><tr><td>en</td><td>Multiply Basis Quantity By Price</td><td>192350002</td></tr><tr><td>en</td><td>Multiply Basis Amount By Percent</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#amountMethod_display name="amountMethod_display">amountMethod_display</a>

First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#basisAmount name="basisAmount">basisAmount</a>

Enter the cost amount of the sales transaction in the transaction currency.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Amount</td></tr><tr><td>description</td><td>Enter the cost amount of the sales transaction in the transaction currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisamount</td></tr></table>

### <a href=#basisAmountBase name="basisAmountBase">basisAmountBase</a>

Enter the cost amount of the sales transaction in the base (organization) currency.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Amount (Base currency)</td></tr><tr><td>description</td><td>Enter the cost amount of the sales transaction in the base (organization) currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisamount_base</td></tr></table>

### <a href=#basisPrice name="basisPrice">basisPrice</a>

Enter the cost price of the sales transaction in transaction currency.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Price</td></tr><tr><td>description</td><td>Enter the cost price of the sales transaction in transaction currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisprice</td></tr></table>

### <a href=#basisPriceBase name="basisPriceBase">basisPriceBase</a>

Enter the cost price of the sales transaction in base (organization) currency.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Price (Base currency)</td></tr><tr><td>description</td><td>Enter the cost price of the sales transaction in base (organization) currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisprice_base</td></tr></table>

### <a href=#basisQuantity name="basisQuantity">basisQuantity</a>

Enter the cost quantity of the sales transaction in the base (organization) currency.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Quantity</td></tr><tr><td>description</td><td>Enter the cost quantity of the sales transaction in the base (organization) currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisquantity</td></tr></table>

### <a href=#billingStatus name="billingStatus">billingStatus</a>

Select the billing status ID.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing status ID</td></tr><tr><td>description</td><td>Select the billing status ID.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_billingstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Unbilled Sales Created</td><td>192350000</td></tr><tr><td>en</td><td>Customer Invoice Created</td><td>192350001</td></tr><tr><td>en</td><td>Customer Invoice Posted</td><td>192350002</td></tr><tr><td>en</td><td>Canceled</td><td>192350003</td></tr><tr><td>en</td><td>Ready to Invoice</td><td>192350004</td></tr><tr><td>en</td><td>Ready to Invoice</td><td>192350004</td></tr><tr><td>en</td><td>Unbilled Sales Created</td><td>192350000</td></tr><tr><td>en</td><td>Customer Invoice Created</td><td>192350001</td></tr><tr><td>en</td><td>Customer Invoice Posted</td><td>192350002</td></tr><tr><td>en</td><td>Canceled</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#billingStatus_display name="billingStatus_display">billingStatus_display</a>

First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#billingType name="billingType">billingType</a>

Select the billing type ID.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing type ID</td></tr><tr><td>description</td><td>Select the billing type ID.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_billingtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Non Chargeable</td><td>192350000</td></tr><tr><td>en</td><td>Chargeable</td><td>192350001</td></tr><tr><td>en</td><td>Complimentary</td><td>192350002</td></tr><tr><td>en</td><td>Not Available</td><td>192350003</td></tr><tr><td>en</td><td>Non Chargeable</td><td>192350000</td></tr><tr><td>en</td><td>Chargeable</td><td>192350001</td></tr><tr><td>en</td><td>Complimentary</td><td>192350002</td></tr><tr><td>en</td><td>Not Available</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#billingType_display name="billingType_display">billingType_display</a>

First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#bookableResource name="bookableResource">bookableResource</a>

Shows the bookable resource for which the actual is recorded.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bookable Resource</td></tr><tr><td>description</td><td>Shows the bookable resource for which the actual is recorded.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookableresource</td></tr></table>

### <a href=#contactCustomer name="contactCustomer">contactCustomer</a>

Select the customer contact.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer contact ID</td></tr><tr><td>description</td><td>Select the customer contact.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contactcustomer</td></tr></table>

### <a href=#contactVendor name="contactVendor">contactVendor</a>

First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contactvendor</td></tr></table>

### <a href=#customerType name="customerType">customerType</a>

Select the customer type ID.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer type ID</td></tr><tr><td>description</td><td>Select the customer type ID.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_customertype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Account</td><td>192350001</td></tr><tr><td>en</td><td>Contact</td><td>192350002</td></tr><tr><td>en</td><td>Account</td><td>192350001</td></tr><tr><td>en</td><td>Contact</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#customerType_display name="customerType_display">customerType_display</a>

First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#documentDate name="documentDate">documentDate</a>

Enter the transaction date of the business event.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document Date</td></tr><tr><td>description</td><td>Enter the transaction date of the business event.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_documentdate</td></tr></table>

### <a href=#endDateTime name="endDateTime">endDateTime</a>

Enter the end date and time for this transaction.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date/Time</td></tr><tr><td>description</td><td>Enter the end date and time for this transaction.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_enddatetime</td></tr></table>

### <a href=#exchangeRateDate name="exchangeRateDate">exchangeRateDate</a>

Enter the date of the exchange rate used for this transaction.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate Date</td></tr><tr><td>description</td><td>Enter the date of the exchange rate used for this transaction.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_exchangeratedate</td></tr></table>

### <a href=#externalDescription name="externalDescription">externalDescription</a>

The external description of the business transaction.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External Description</td></tr><tr><td>description</td><td>The external description of the business transaction.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_externaldescription</td></tr></table>

### <a href=#externalReferenceDate name="externalReferenceDate">externalReferenceDate</a>

Stores a date from an external system, such as a journal entry voucher date from an ERP system  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External Reference Date</td></tr><tr><td>description</td><td>Stores a date from an external system, such as a journal entry voucher date from an ERP system</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_externalreferencedate</td></tr></table>

### <a href=#externalReferenceID name="externalReferenceID">externalReferenceID</a>

Stores an ID from an external system, such as the journal entry voucher number from an ERP system.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External Reference ID</td></tr><tr><td>description</td><td>Stores an ID from an external system, such as the journal entry voucher number from an ERP system.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_externalreferenceid</td></tr></table>

### <a href=#invoice name="invoice">invoice</a>

The unique identifier of an invoice.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice</td></tr><tr><td>description</td><td>The unique identifier of an invoice.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_invoice</td></tr></table>

### <a href=#isJournalized name="isJournalized">isJournalized</a>

First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Journalized</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_isjournalized</td></tr></table>

### <a href=#percent name="percent">percent</a>

Enter the percent.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percent</td></tr><tr><td>description</td><td>Enter the percent.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_percent</td></tr></table>

### <a href=#price name="price">price</a>

Enter the price in the transaction currency.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price</td></tr><tr><td>description</td><td>Enter the price in the transaction currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_price</td></tr></table>

### <a href=#priceBase name="priceBase">priceBase</a>

Enter the price in the base (organization) currency.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price (Base)</td></tr><tr><td>description</td><td>Enter the price in the base (organization) currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_price_base</td></tr></table>

### <a href=#priceList name="priceList">priceList</a>

Select the price list.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price list ID</td></tr><tr><td>description</td><td>Select the price list.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_pricelist</td></tr></table>

### <a href=#product name="product">product</a>

Select the product ID.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product ID</td></tr><tr><td>description</td><td>Select the product ID.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_product</td></tr></table>

### <a href=#quantity name="quantity">quantity</a>

Enter the quantity.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity</td></tr><tr><td>description</td><td>Enter the quantity.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_quantity</td></tr></table>

### <a href=#salesContract name="salesContract">salesContract</a>

Select the project contract.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Contract ID</td></tr><tr><td>description</td><td>Select the project contract.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salescontract</td></tr></table>

### <a href=#salesContractLine name="salesContractLine">salesContractLine</a>

(Deprecated) Type the project contract line.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Contract Line</td></tr><tr><td>description</td><td>(Deprecated) Type the project contract line.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salescontractline</td></tr></table>

### <a href=#startDateTime name="startDateTime">startDateTime</a>

Enter the start date and time.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date/Time</td></tr><tr><td>description</td><td>Enter the start date and time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_startdatetime</td></tr></table>

### <a href=#transactionClassification name="transactionClassification">transactionClassification</a>

Shows the transaction classification of this transaction.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Class</td></tr><tr><td>description</td><td>Shows the transaction classification of this transaction.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactionclassification</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Time</td><td>192350000</td></tr><tr><td>en</td><td>Expense</td><td>192350001</td></tr><tr><td>en</td><td>Material</td><td>192350002</td></tr><tr><td>en</td><td>Milestone</td><td>192350003</td></tr><tr><td>en</td><td>Fee</td><td>192350004</td></tr><tr><td>en</td><td>Time</td><td>192350000</td></tr><tr><td>en</td><td>Expense</td><td>192350001</td></tr><tr><td>en</td><td>Material</td><td>192350002</td></tr><tr><td>en</td><td>Milestone</td><td>192350003</td></tr><tr><td>en</td><td>Fee</td><td>192350004</td></tr><tr><td>en</td><td>Tax</td><td>690970002</td></tr><tr><td>en</td><td>Tax</td><td>690970002</td></tr></table></td></tr></table>

### <a href=#transactionClassification_display name="transactionClassification_display">transactionClassification_display</a>

First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionTypeCode name="transactionTypeCode">transactionTypeCode</a>

Shows the transaction type of this transaction.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Type</td></tr><tr><td>description</td><td>Shows the transaction type of this transaction.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactiontypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Cost</td><td>192350000</td></tr><tr><td>en</td><td>Project Contract</td><td>192350004</td></tr><tr><td>en</td><td>Unbilled Sales</td><td>192350005</td></tr><tr><td>en</td><td>Billed Sales</td><td>192350006</td></tr><tr><td>en</td><td>Resourcing Unit Cost</td><td>192350007</td></tr><tr><td>en</td><td>Inter-Organizational Sales</td><td>192350008</td></tr><tr><td>en</td><td>Cost</td><td>192350000</td></tr><tr><td>en</td><td>Project Contract</td><td>192350004</td></tr><tr><td>en</td><td>Unbilled Sales</td><td>192350005</td></tr><tr><td>en</td><td>Billed Sales</td><td>192350006</td></tr><tr><td>en</td><td>Resourcing Unit Cost</td><td>192350007</td></tr><tr><td>en</td><td>Inter-Organizational Sales</td><td>192350008</td></tr></table></td></tr></table>

### <a href=#transactionTypeCode_display name="transactionTypeCode_display">transactionTypeCode_display</a>

First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#unit name="unit">unit</a>

Select the unit of measure.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit of measure</td></tr><tr><td>description</td><td>Select the unit of measure.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_unit</td></tr></table>

### <a href=#unitSchedule name="unitSchedule">unitSchedule</a>

Select the unit schedule.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit Schedule</td></tr><tr><td>description</td><td>Select the unit schedule.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_unitschedule</td></tr></table>

### <a href=#vendorType name="vendorType">vendorType</a>

First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_vendortype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Account</td><td>192350001</td></tr><tr><td>en</td><td>Contact</td><td>192350002</td></tr><tr><td>en</td><td>Account</td><td>192350001</td></tr><tr><td>en</td><td>Contact</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#vendorType_display name="vendorType_display">vendorType_display</a>

First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#contractingUnit name="contractingUnit">contractingUnit</a>

Select the organizational unit ID for the contract.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contracting Unit</td></tr><tr><td>description</td><td>Select the organizational unit ID for the contract.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contractorganizationalunitid</td></tr></table>

### <a href=#project name="project">project</a>

Select the project ID.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project ID</td></tr><tr><td>description</td><td>Select the project ID.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_project</td></tr></table>

### <a href=#resourceCategory name="resourceCategory">resourceCategory</a>

Select the role ID of the resource performing the work.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource role ID</td></tr><tr><td>description</td><td>Select the role ID of the resource performing the work.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcecategory</td></tr></table>

### <a href=#resourceOrganizationalUnitId name="resourceOrganizationalUnitId">resourceOrganizationalUnitId</a>

Organizational unit at the time the actual was registered of the resource who performed the work.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resourcing Unit</td></tr><tr><td>description</td><td>Organizational unit at the time the actual was registered of the resource who performed the work.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourceorganizationalunitid</td></tr></table>

### <a href=#salesContractLineId name="salesContractLineId">salesContractLineId</a>

Unique identifier for Project Contract Line associated with Actual.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Contract Line</td></tr><tr><td>description</td><td>Unique identifier for Project Contract Line associated with Actual.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salescontractlineid</td></tr></table>

### <a href=#task name="task">task</a>

Select the task.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Task ID</td></tr><tr><td>description</td><td>Select the task.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_task</td></tr></table>

### <a href=#transactionCategory name="transactionCategory">transactionCategory</a>

Select the transaction category.  
First included in: scheduling/Actual (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction category ID</td></tr><tr><td>description</td><td>Select the transaction category.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactioncategory</td></tr></table>
