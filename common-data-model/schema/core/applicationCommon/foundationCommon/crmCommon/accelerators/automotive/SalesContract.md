---
title: SalesContract - Common Data Model | Microsoft Docs
description: Contract involving the sale of one or more vehicle or device to a customer.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Sales Contract

Contract involving the sale of one or more vehicle or device to a customer.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/automotive/SalesContract.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/automotive/SalesContract  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[ownerId](#ownerId)|Owner Id|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[contractDate](#contractDate)|The origination date of the sales contract.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[customerIdType](#customerIdType)|The type of customer, either Account or Contact.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[customerId](#customerId)|The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[dealId](#dealId)|The parent deal associated with this sales contract.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[description](#description)|Description of the sales contact.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[endDate](#endDate)|The date at which the sales contract will end.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[finalBalloonPayment](#finalBalloonPayment)|The amount of the final payment due at maturity of the sales contract.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[finalBalloonPaymentBase](#finalBalloonPaymentBase)|Value of the final balloon payment in base currency.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[name](#name)|Name of the sales contract detail.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[originationCommission](#originationCommission)|The commission amount paid for origination of the loan.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[originationCommissionBase](#originationCommissionBase)|Value of the origination commission in base currency.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[salesContractId](#salesContractId)|Unique identifier for entity instances|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[salesContractTypeId](#salesContractTypeId)|Category of the sales contract (cash, finance, or lease).|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[sellingPrice](#sellingPrice)|The price for which the vehicle or device is sold.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[sellingPriceBase](#sellingPriceBase)|Value of the Selling Price in base currency.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[startDate](#startDate)|The day at which the sales contract takes effect.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[totalAdd](#totalAdd)|The price charged for all add-ons included in this sales contract.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[totalAddBase](#totalAddBase)|Value of the total add-ons price in base currency.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[totalAddOnsCost](#totalAddOnsCost)|The cost for all add-ons included in this sales contract.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[totalAddOnsCostBase](#totalAddOnsCostBase)|Value of the total add-ons cost in base currency.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[totalDownpayment](#totalDownpayment)|The down payment being applied at origination of the loan.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[totalDownpaymentBase](#totalDownpaymentBase)|Value of the total down payment in base currency.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[totalMonthlyPayment](#totalMonthlyPayment)|The amount to be paid each month for the life of the loan.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[totalMonthlyPaymentBase](#totalMonthlyPaymentBase)|Value of the total monthly payment in base currency.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[totalServiceContractCost](#totalServiceContractCost)|The total cost of the service contract associated with this sale.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[totalServiceContractCostBase](#totalServiceContractCostBase)|Value of the total service contract cost in base currency.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[totalServiceContractsPrice](#totalServiceContractsPrice)|The price changed for the service contract associated with this sale.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[totalServiceContractsPriceBase](#totalServiceContractsPriceBase)|Value of the total service contracts price in base currency.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[totalTaxesAndFees](#totalTaxesAndFees)|Total of all taxes and fees applied to this sales contract.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[totalTaxesAndFeesBase](#totalTaxesAndFeesBase)|Value of the total taxes and fees in base currency.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[totalTradeIn](#totalTradeIn)|The value set for the trade in included in this sales contract.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[totalTradeInBase](#totalTradeInBase)|Value of the total trade in in base currency.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[stateCode](#stateCode)|Status of the Sales Contract|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[stateCode_display](#stateCode_display)||<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[statusCode](#statusCode)|Reason for the status of the Sales Contract|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[statusCode_display](#statusCode_display)||<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="SalesContract.md" target="_blank">automotive/SalesContract</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#contractDate name="contractDate">contractDate</a>

The origination date of the sales contract.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract Date</td></tr><tr><td>description</td><td>The origination date of the sales contract.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msauto_contractdate</td></tr></table>

### <a href=#customerIdType name="customerIdType">customerIdType</a>

The type of customer, either Account or Contact.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>The type of customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>customeridtype</td></tr></table>

### <a href=#customerId name="customerId">customerId</a>

The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerid</td></tr></table>

### <a href=#dealId name="dealId">dealId</a>

The parent deal associated with this sales contract.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deal</td></tr><tr><td>description</td><td>The parent deal associated with this sales contract.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_dealid</td></tr></table>

### <a href=#description name="description">description</a>

Description of the sales contact.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the sales contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>sourceName</td><td>msauto_description</td></tr></table>

### <a href=#endDate name="endDate">endDate</a>

The date at which the sales contract will end.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date</td></tr><tr><td>description</td><td>The date at which the sales contract will end.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msauto_enddate</td></tr></table>

### <a href=#finalBalloonPayment name="finalBalloonPayment">finalBalloonPayment</a>

The amount of the final payment due at maturity of the sales contract.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Final Balloon Payment</td></tr><tr><td>description</td><td>The amount of the final payment due at maturity of the sales contract.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_finalballoonpayment</td></tr></table>

### <a href=#finalBalloonPaymentBase name="finalBalloonPaymentBase">finalBalloonPaymentBase</a>

Value of the final balloon payment in base currency.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Final Balloon Payment (Base)</td></tr><tr><td>description</td><td>Value of the final balloon payment in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_finalballoonpayment_base</td></tr></table>

### <a href=#name name="name">name</a>

Name of the sales contract detail.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the sales contract detail.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msauto_name</td></tr></table>

### <a href=#originationCommission name="originationCommission">originationCommission</a>

The commission amount paid for origination of the loan.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Origination Commission</td></tr><tr><td>description</td><td>The commission amount paid for origination of the loan.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_originationcommission</td></tr></table>

### <a href=#originationCommissionBase name="originationCommissionBase">originationCommissionBase</a>

Value of the origination commission in base currency.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Origination Commission (Base)</td></tr><tr><td>description</td><td>Value of the origination commission in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_originationcommission_base</td></tr></table>

### <a href=#salesContractId name="salesContractId">salesContractId</a>

Unique identifier for entity instances  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Contract</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_salescontractid</td></tr></table>

### <a href=#salesContractTypeId name="salesContractTypeId">salesContractTypeId</a>

Category of the sales contract (cash, finance, or lease).  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Contract Type</td></tr><tr><td>description</td><td>Category of the sales contract (cash, finance, or lease).</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msauto_salescontracttypeid</td></tr></table>

### <a href=#sellingPrice name="sellingPrice">sellingPrice</a>

The price for which the vehicle or device is sold.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Selling Price</td></tr><tr><td>description</td><td>The price for which the vehicle or device is sold.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_sellingprice</td></tr></table>

### <a href=#sellingPriceBase name="sellingPriceBase">sellingPriceBase</a>

Value of the Selling Price in base currency.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Selling Price (Base)</td></tr><tr><td>description</td><td>Value of the Selling Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_sellingprice_base</td></tr></table>

### <a href=#startDate name="startDate">startDate</a>

The day at which the sales contract takes effect.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>The day at which the sales contract takes effect.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msauto_startdate</td></tr></table>

### <a href=#totalAdd name="totalAdd">totalAdd</a>

The price charged for all add-ons included in this sales contract.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Add Ons Price</td></tr><tr><td>description</td><td>The price charged for all add-ons included in this sales contract.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_totaladd</td></tr></table>

### <a href=#totalAddBase name="totalAddBase">totalAddBase</a>

Value of the total add-ons price in base currency.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Add Ons Price (Base)</td></tr><tr><td>description</td><td>Value of the total add-ons price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_totaladd_base</td></tr></table>

### <a href=#totalAddOnsCost name="totalAddOnsCost">totalAddOnsCost</a>

The cost for all add-ons included in this sales contract.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Add Ons Cost</td></tr><tr><td>description</td><td>The cost for all add-ons included in this sales contract.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_totaladdonscost</td></tr></table>

### <a href=#totalAddOnsCostBase name="totalAddOnsCostBase">totalAddOnsCostBase</a>

Value of the total add-ons cost in base currency.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Add Ons Cost (Base)</td></tr><tr><td>description</td><td>Value of the total add-ons cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_totaladdonscost_base</td></tr></table>

### <a href=#totalDownpayment name="totalDownpayment">totalDownpayment</a>

The down payment being applied at origination of the loan.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Downpayment</td></tr><tr><td>description</td><td>The down payment being applied at origination of the loan.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_totaldownpayment</td></tr></table>

### <a href=#totalDownpaymentBase name="totalDownpaymentBase">totalDownpaymentBase</a>

Value of the total down payment in base currency.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Downpayment (Base)</td></tr><tr><td>description</td><td>Value of the total down payment in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_totaldownpayment_base</td></tr></table>

### <a href=#totalMonthlyPayment name="totalMonthlyPayment">totalMonthlyPayment</a>

The amount to be paid each month for the life of the loan.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Monthly Payment</td></tr><tr><td>description</td><td>The amount to be paid each month for the life of the loan.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_totalmonthlypayment</td></tr></table>

### <a href=#totalMonthlyPaymentBase name="totalMonthlyPaymentBase">totalMonthlyPaymentBase</a>

Value of the total monthly payment in base currency.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Monthly Payment (Base)</td></tr><tr><td>description</td><td>Value of the total monthly payment in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_totalmonthlypayment_base</td></tr></table>

### <a href=#totalServiceContractCost name="totalServiceContractCost">totalServiceContractCost</a>

The total cost of the service contract associated with this sale.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Service Contract Cost</td></tr><tr><td>description</td><td>The total cost of the service contract associated with this sale.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_totalservicecontractcost</td></tr></table>

### <a href=#totalServiceContractCostBase name="totalServiceContractCostBase">totalServiceContractCostBase</a>

Value of the total service contract cost in base currency.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Service Contract Cost (Base)</td></tr><tr><td>description</td><td>Value of the total service contract cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_totalservicecontractcost_base</td></tr></table>

### <a href=#totalServiceContractsPrice name="totalServiceContractsPrice">totalServiceContractsPrice</a>

The price changed for the service contract associated with this sale.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Service Contracts Price</td></tr><tr><td>description</td><td>The price changed for the service contract associated with this sale.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_totalservicecontractsprice</td></tr></table>

### <a href=#totalServiceContractsPriceBase name="totalServiceContractsPriceBase">totalServiceContractsPriceBase</a>

Value of the total service contracts price in base currency.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Service Contracts Price (Base)</td></tr><tr><td>description</td><td>Value of the total service contracts price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_totalservicecontractsprice_base</td></tr></table>

### <a href=#totalTaxesAndFees name="totalTaxesAndFees">totalTaxesAndFees</a>

Total of all taxes and fees applied to this sales contract.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Taxes and Fees</td></tr><tr><td>description</td><td>Total of all taxes and fees applied to this sales contract.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_totaltaxesandfees</td></tr></table>

### <a href=#totalTaxesAndFeesBase name="totalTaxesAndFeesBase">totalTaxesAndFeesBase</a>

Value of the total taxes and fees in base currency.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Taxes and Fees (Base)</td></tr><tr><td>description</td><td>Value of the total taxes and fees in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_totaltaxesandfees_base</td></tr></table>

### <a href=#totalTradeIn name="totalTradeIn">totalTradeIn</a>

The value set for the trade in included in this sales contract.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Trade In</td></tr><tr><td>description</td><td>The value set for the trade in included in this sales contract.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_totaltradein</td></tr></table>

### <a href=#totalTradeInBase name="totalTradeInBase">totalTradeInBase</a>

Value of the total trade in in base currency.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Trade In (Base)</td></tr><tr><td>description</td><td>Value of the total trade in in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msauto_totaltradein_base</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Sales Contract  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Sales Contract</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Sales Contract  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Sales Contract</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Draft</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Signed</td><td>972230000</td><td>0</td></tr><tr><td>en</td><td>Active</td><td>972230001</td><td>0</td></tr><tr><td>en</td><td>Expired</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>972230002</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: automotive/SalesContract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>
