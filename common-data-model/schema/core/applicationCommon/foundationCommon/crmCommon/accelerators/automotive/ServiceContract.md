---
title: ServiceContract - Common Data Model | Microsoft Docs
description: Contract involving the service of one or more vehicles or devices owned by a customer.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Service Contract

Contract involving the service of one or more vehicles or devices owned by a customer.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/automotive/ServiceContract.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/automotive/ServiceContract  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[ownerId](#ownerId)|Owner Id|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[actualCost](#actualCost)|The actual charged amount for this service contract.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[actualCostBase](#actualCostBase)|Value of the actual cost in base currency.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[actualRevenue](#actualRevenue)|The actual revenue earned on the service contract.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[actualRevenueBase](#actualRevenueBase)|Value of the actual revenue in base currency.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[commissionAmount](#commissionAmount)|The commission earned on the service contract.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[commissionAmountBase](#commissionAmountBase)|Value of the commission amount in base currency.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[contractStatus](#contractStatus)|The current status of the contract (open, closed or canceled).|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[contractStatus_display](#contractStatus_display)||<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[customerIdType](#customerIdType)|The type of customer, either Account or Contact.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[customerId](#customerId)|The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[customerPrice](#customerPrice)|The price paid by the customer for this service.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[customerPriceBase](#customerPriceBase)|Value of the customer price in base currency.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[description](#description)|Description of the service contract.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[endDate](#endDate)|The date at which this service contract ends.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[estimatedCost](#estimatedCost)|The estimated cost of this service contract.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[estimatedCostBase](#estimatedCostBase)|Value of the estimated cost in base currency.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[estimatedRevenue](#estimatedRevenue)|The revenue estimate on this service contract.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[estimatedRevenueBase](#estimatedRevenueBase)|Value of the estimated revenue in base currency.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[name](#name)|Name of the service contract.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[providerAccountId](#providerAccountId)|The company providing this service contract.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[retailPrice](#retailPrice)|The retail price of this service contract.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[retailPriceBase](#retailPriceBase)|Value of the retail price in base currency.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[serviceContractId](#serviceContractId)|Unique identifier for entity instances|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[serviceContractTypeId](#serviceContractTypeId)|Category of the service contract (powertrain, named component, exclusionary, etc.).|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[startDate](#startDate)|The date at which this service contract starts.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[stateCode](#stateCode)|Status of the Service Contract|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[stateCode_display](#stateCode_display)||<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[statusCode](#statusCode)|Reason for the status of the Service Contract|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[statusCode_display](#statusCode_display)||<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="ServiceContract.md" target="_blank">automotive/ServiceContract</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#actualCost name="actualCost">actualCost</a>

The actual charged amount for this service contract.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Cost</td></tr><tr><td>description</td><td>The actual charged amount for this service contract.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_actualcost</td></tr></table>

### <a href=#actualCostBase name="actualCostBase">actualCostBase</a>

Value of the actual cost in base currency.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Cost (Base)</td></tr><tr><td>description</td><td>Value of the actual cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_actualcost_base</td></tr></table>

### <a href=#actualRevenue name="actualRevenue">actualRevenue</a>

The actual revenue earned on the service contract.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Revenue</td></tr><tr><td>description</td><td>The actual revenue earned on the service contract.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_actualrevenue</td></tr></table>

### <a href=#actualRevenueBase name="actualRevenueBase">actualRevenueBase</a>

Value of the actual revenue in base currency.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Revenue (Base)</td></tr><tr><td>description</td><td>Value of the actual revenue in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_actualrevenue_base</td></tr></table>

### <a href=#commissionAmount name="commissionAmount">commissionAmount</a>

The commission earned on the service contract.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commission Amount</td></tr><tr><td>description</td><td>The commission earned on the service contract.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_commissionamount</td></tr></table>

### <a href=#commissionAmountBase name="commissionAmountBase">commissionAmountBase</a>

Value of the commission amount in base currency.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commission Amount (Base)</td></tr><tr><td>description</td><td>Value of the commission amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_commissionamount_base</td></tr></table>

### <a href=#contractStatus name="contractStatus">contractStatus</a>

The current status of the contract (open, closed or canceled).  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract Status</td></tr><tr><td>description</td><td>The current status of the contract (open, closed or canceled).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msauto_contractstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#contractStatus_display name="contractStatus_display">contractStatus_display</a>

First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#customerIdType name="customerIdType">customerIdType</a>

The type of customer, either Account or Contact.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>The type of customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>customeridtype</td></tr></table>

### <a href=#customerId name="customerId">customerId</a>

The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerid</td></tr></table>

### <a href=#customerPrice name="customerPrice">customerPrice</a>

The price paid by the customer for this service.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Price</td></tr><tr><td>description</td><td>The price paid by the customer for this service.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_customerprice</td></tr></table>

### <a href=#customerPriceBase name="customerPriceBase">customerPriceBase</a>

Value of the customer price in base currency.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Price (Base)</td></tr><tr><td>description</td><td>Value of the customer price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_customerprice_base</td></tr></table>

### <a href=#description name="description">description</a>

Description of the service contract.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the service contract.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_description</td></tr></table>

### <a href=#endDate name="endDate">endDate</a>

The date at which this service contract ends.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date</td></tr><tr><td>description</td><td>The date at which this service contract ends.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msauto_enddate</td></tr></table>

### <a href=#estimatedCost name="estimatedCost">estimatedCost</a>

The estimated cost of this service contract.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Cost</td></tr><tr><td>description</td><td>The estimated cost of this service contract.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_estimatedcost</td></tr></table>

### <a href=#estimatedCostBase name="estimatedCostBase">estimatedCostBase</a>

Value of the estimated cost in base currency.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Cost (Base)</td></tr><tr><td>description</td><td>Value of the estimated cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_estimatedcost_base</td></tr></table>

### <a href=#estimatedRevenue name="estimatedRevenue">estimatedRevenue</a>

The revenue estimate on this service contract.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Revenue</td></tr><tr><td>description</td><td>The revenue estimate on this service contract.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_estimatedrevenue</td></tr></table>

### <a href=#estimatedRevenueBase name="estimatedRevenueBase">estimatedRevenueBase</a>

Value of the estimated revenue in base currency.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Revenue (Base)</td></tr><tr><td>description</td><td>Value of the estimated revenue in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_estimatedrevenue_base</td></tr></table>

### <a href=#name name="name">name</a>

Name of the service contract.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the service contract.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_name</td></tr></table>

### <a href=#providerAccountId name="providerAccountId">providerAccountId</a>

The company providing this service contract.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Provider Account</td></tr><tr><td>description</td><td>The company providing this service contract.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_provideraccountid</td></tr></table>

### <a href=#retailPrice name="retailPrice">retailPrice</a>

The retail price of this service contract.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Retail Price</td></tr><tr><td>description</td><td>The retail price of this service contract.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_retailprice</td></tr></table>

### <a href=#retailPriceBase name="retailPriceBase">retailPriceBase</a>

Value of the retail price in base currency.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Retail Price (Base)</td></tr><tr><td>description</td><td>Value of the retail price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_retailprice_base</td></tr></table>

### <a href=#serviceContractId name="serviceContractId">serviceContractId</a>

Unique identifier for entity instances  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service Contract</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_servicecontractid</td></tr></table>

### <a href=#serviceContractTypeId name="serviceContractTypeId">serviceContractTypeId</a>

Category of the service contract (powertrain, named component, exclusionary, etc.).  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service Contract Type</td></tr><tr><td>description</td><td>Category of the service contract (powertrain, named component, exclusionary, etc.).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_servicecontracttype</td></tr></table>

### <a href=#startDate name="startDate">startDate</a>

The date at which this service contract starts.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>The date at which this service contract starts.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msauto_startdate</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Service Contract  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Service Contract</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Service Contract  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Service Contract</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: automotive/ServiceContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>
