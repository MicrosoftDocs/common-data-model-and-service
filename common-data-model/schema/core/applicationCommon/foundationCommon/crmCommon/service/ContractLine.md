---
title: ContractLine - Common Data Model | Microsoft Docs
description: Line item in a contract that specifies the type of service a customer is entitled to.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Contract Line

Line item in a contract that specifies the type of service a customer is entitled to.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/service/ContractLine.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/service/ContractLine  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[ownerId](#ownerId)|Owner Id|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[owningUser](#owningUser)|Unique identifier for the user that owns the record.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[contractDetailId](#contractDetailId)|Unique identifier of the contract line.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[title](#title)|Type a title or name that describes the contract line.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[activeOn](#activeOn)|Enter the date when the contract line becomes active.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[allotmentsOverage](#allotmentsOverage)|Shows the number of minutes over the Total Allotments field that have been spent on resolved cases related to the contract line.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[allotmentsRemaining](#allotmentsRemaining)|Shows the number of cases or minutes remaining, based on the resolved cases logged to the contract line.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[allotmentsUsed](#allotmentsUsed)|Shows the number of cases or minutes used in the resolved cases on the contract line.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[contractId](#contractId)|Unique identifier of the contract associated with the contract line.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[contractStateCode](#contractStateCode)|Status of the contract.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[contractStateCode_display](#contractStateCode_display)||<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[customerIdType](#customerIdType)|The type of customer, either Account or Contact.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[customerId](#customerId)|The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[discount](#discount)|Type the discount amount for the contract line to deduct any negotiated or other savings from the net amount due.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[discountBase](#discountBase)|Value of the Discount in base currency.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[discountPercentage](#discountPercentage)|Type the discount rate that should be applied to the Total Price, for use in calculating the net amount due for the contract line.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[effectivityCalendar](#effectivityCalendar)|Days of the week and times for which the contract line item is effective.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[expiresOn](#expiresOn)|Enter the date when the contract line expires. The date is automatically filled with the contract date, but you can change it if required.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[initialQuantity](#initialQuantity)|Type the number of units of the specified product or service that are eligible for support on the contract line.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[lineItemOrder](#lineItemOrder)|Type the line item number for the contract line to easily identify the contract line and make sure it's listed in the correct order in the parent contract.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[net](#net)|Shows the total charge to the customer for the contract line, calculated as the Total Price minus any discounts.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[netBase](#netBase)|Value of the Net in base currency.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[price](#price)|Type the total service charge for the contract line before any discounts are credited.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[priceBase](#priceBase)|Value of the Total Price in base currency.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[productId](#productId)|Choose the product that is eligible for services on the contract line.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[productSerialNumber](#productSerialNumber)|Type the serial number for the product that is eligible for services on the contract line.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[rate](#rate)|Shows the cost per case or minute, calculated by dividing the Total Price value by the total number of cases or minutes allocated to the contract line.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[rateBase](#rateBase)|Value of the Rate in base currency.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[serviceAddress](#serviceAddress)|Choose the address for the customer account or contact where the services are provided.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[serviceContractUnitsCode](#serviceContractUnitsCode)|Select the unit type allotted in the contract line, such as cases or minutes, to determine the level of support.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[serviceContractUnitsCode_display](#serviceContractUnitsCode_display)||<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[stateCode](#stateCode)|Shows whether the contract line is existing, renewed, canceled, or expired. You can't edit a contract line after it is saved, regardless of the status.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[stateCode_display](#stateCode_display)||<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[statusCode](#statusCode)|Select the contract line's status.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[statusCode_display](#statusCode_display)||<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[totalAllotments](#totalAllotments)|Type the total number of minutes or cases allowed for the contract line.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[uoMId](#uoMId)|Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[uoMScheduleId](#uoMScheduleId)|Unique identifier of the unit group associated with the contract line.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[accountId](#accountId)|Unique identifier of the account with which the contract is associated.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|
|[contactId](#contactId)|Unique identifier for the contact associated with the contract line.|<a href="ContractLine.md" target="_blank">service/ContractLine</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier for the user that owns the record.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier for the user that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#contractDetailId name="contractDetailId">contractDetailId</a>

Unique identifier of the contract line.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract Line</td></tr><tr><td>description</td><td>Unique identifier of the contract line.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>contractdetailid</td></tr></table>

### <a href=#title name="title">title</a>

Type a title or name that describes the contract line.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Title</td></tr><tr><td>description</td><td>Type a title or name that describes the contract line.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>title</td></tr></table>

### <a href=#activeOn name="activeOn">activeOn</a>

Enter the date when the contract line becomes active.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Enter the date when the contract line becomes active.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>activeon</td></tr></table>

### <a href=#allotmentsOverage name="allotmentsOverage">allotmentsOverage</a>

Shows the number of minutes over the Total Allotments field that have been spent on resolved cases related to the contract line.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allotments Overage</td></tr><tr><td>description</td><td>Shows the number of minutes over the Total Allotments field that have been spent on resolved cases related to the contract line.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>allotmentsoverage</td></tr></table>

### <a href=#allotmentsRemaining name="allotmentsRemaining">allotmentsRemaining</a>

Shows the number of cases or minutes remaining, based on the resolved cases logged to the contract line.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allotments Remaining</td></tr><tr><td>description</td><td>Shows the number of cases or minutes remaining, based on the resolved cases logged to the contract line.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>allotmentsremaining</td></tr></table>

### <a href=#allotmentsUsed name="allotmentsUsed">allotmentsUsed</a>

Shows the number of cases or minutes used in the resolved cases on the contract line.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allotments Used</td></tr><tr><td>description</td><td>Shows the number of cases or minutes used in the resolved cases on the contract line.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>allotmentsused</td></tr></table>

### <a href=#contractId name="contractId">contractId</a>

Unique identifier of the contract associated with the contract line.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract</td></tr><tr><td>description</td><td>Unique identifier of the contract associated with the contract line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>contractid</td></tr></table>

### <a href=#contractStateCode name="contractStateCode">contractStateCode</a>

Status of the contract.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract State</td></tr><tr><td>description</td><td>Status of the contract.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>contractstatecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#contractStateCode_display name="contractStateCode_display">contractStateCode_display</a>

First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#customerIdType name="customerIdType">customerIdType</a>

The type of customer, either Account or Contact.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>The type of customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>customeridtype</td></tr></table>

### <a href=#customerId name="customerId">customerId</a>

The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerid</td></tr></table>

### <a href=#discount name="discount">discount</a>

Type the discount amount for the contract line to deduct any negotiated or other savings from the net amount due.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount</td></tr><tr><td>description</td><td>Type the discount amount for the contract line to deduct any negotiated or other savings from the net amount due.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>discount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#discountBase name="discountBase">discountBase</a>

Value of the Discount in base currency.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount (Base)</td></tr><tr><td>description</td><td>Value of the Discount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>discount_base</td></tr></table>

### <a href=#discountPercentage name="discountPercentage">discountPercentage</a>

Type the discount rate that should be applied to the Total Price, for use in calculating the net amount due for the contract line.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount (%)</td></tr><tr><td>description</td><td>Type the discount rate that should be applied to the Total Price, for use in calculating the net amount due for the contract line.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>discountpercentage</td></tr></table>

### <a href=#effectivityCalendar name="effectivityCalendar">effectivityCalendar</a>

Days of the week and times for which the contract line item is effective.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Support Calendar</td></tr><tr><td>description</td><td>Days of the week and times for which the contract line item is effective.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>168</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>effectivitycalendar</td></tr></table>

### <a href=#expiresOn name="expiresOn">expiresOn</a>

Enter the date when the contract line expires. The date is automatically filled with the contract date, but you can change it if required.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date</td></tr><tr><td>description</td><td>Enter the date when the contract line expires. The date is automatically filled with the contract date, but you can change it if required.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>expireson</td></tr></table>

### <a href=#initialQuantity name="initialQuantity">initialQuantity</a>

Type the number of units of the specified product or service that are eligible for support on the contract line.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity</td></tr><tr><td>description</td><td>Type the number of units of the specified product or service that are eligible for support on the contract line.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>initialquantity</td></tr></table>

### <a href=#lineItemOrder name="lineItemOrder">lineItemOrder</a>

Type the line item number for the contract line to easily identify the contract line and make sure it's listed in the correct order in the parent contract.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line Item Order</td></tr><tr><td>description</td><td>Type the line item number for the contract line to easily identify the contract line and make sure it's listed in the correct order in the parent contract.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lineitemorder</td></tr></table>

### <a href=#net name="net">net</a>

Shows the total charge to the customer for the contract line, calculated as the Total Price minus any discounts.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Net</td></tr><tr><td>description</td><td>Shows the total charge to the customer for the contract line, calculated as the Total Price minus any discounts.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>net</td></tr></table>

### <a href=#netBase name="netBase">netBase</a>

Value of the Net in base currency.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Net (Base)</td></tr><tr><td>description</td><td>Value of the Net in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>net_base</td></tr></table>

### <a href=#price name="price">price</a>

Type the total service charge for the contract line before any discounts are credited.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Price</td></tr><tr><td>description</td><td>Type the total service charge for the contract line before any discounts are credited.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>price</td></tr></table>

### <a href=#priceBase name="priceBase">priceBase</a>

Value of the Total Price in base currency.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Price (Base)</td></tr><tr><td>description</td><td>Value of the Total Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>price_base</td></tr></table>

### <a href=#productId name="productId">productId</a>

Choose the product that is eligible for services on the contract line.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product</td></tr><tr><td>description</td><td>Choose the product that is eligible for services on the contract line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>productid</td></tr></table>

### <a href=#productSerialNumber name="productSerialNumber">productSerialNumber</a>

Type the serial number for the product that is eligible for services on the contract line.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Serial Number</td></tr><tr><td>description</td><td>Type the serial number for the product that is eligible for services on the contract line.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>productserialnumber</td></tr></table>

### <a href=#rate name="rate">rate</a>

Shows the cost per case or minute, calculated by dividing the Total Price value by the total number of cases or minutes allocated to the contract line.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rate</td></tr><tr><td>description</td><td>Shows the cost per case or minute, calculated by dividing the Total Price value by the total number of cases or minutes allocated to the contract line.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rate</td></tr></table>

### <a href=#rateBase name="rateBase">rateBase</a>

Value of the Rate in base currency.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rate (Base)</td></tr><tr><td>description</td><td>Value of the Rate in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rate_base</td></tr></table>

### <a href=#serviceAddress name="serviceAddress">serviceAddress</a>

Choose the address for the customer account or contact where the services are provided.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Location</td></tr><tr><td>description</td><td>Choose the address for the customer account or contact where the services are provided.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>serviceaddress</td></tr></table>

### <a href=#serviceContractUnitsCode name="serviceContractUnitsCode">serviceContractUnitsCode</a>

Select the unit type allotted in the contract line, such as cases or minutes, to determine the level of support.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service Contract Units</td></tr><tr><td>description</td><td>Select the unit type allotted in the contract line, such as cases or minutes, to determine the level of support.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>servicecontractunitscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#serviceContractUnitsCode_display name="serviceContractUnitsCode_display">serviceContractUnitsCode_display</a>

First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the contract line is existing, renewed, canceled, or expired. You can't edit a contract line after it is saved, regardless of the status.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the contract line is existing, renewed, canceled, or expired. You can't edit a contract line after it is saved, regardless of the status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Existing</td><td>0</td></tr><tr><td>en</td><td>Renewed</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>2</td></tr><tr><td>en</td><td>Expired</td><td>3</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the contract line's status.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the contract line's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>New</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Renewed</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>3</td><td>2</td></tr><tr><td>en</td><td>Expired</td><td>4</td><td>3</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#totalAllotments name="totalAllotments">totalAllotments</a>

Type the total number of minutes or cases allowed for the contract line.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Allotments</td></tr><tr><td>description</td><td>Type the total number of minutes or cases allowed for the contract line.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>totalallotments</td></tr></table>

### <a href=#uoMId name="uoMId">uoMId</a>

Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit</td></tr><tr><td>description</td><td>Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>uomid</td></tr></table>

### <a href=#uoMScheduleId name="uoMScheduleId">uoMScheduleId</a>

Unique identifier of the unit group associated with the contract line.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit Schedule</td></tr><tr><td>description</td><td>Unique identifier of the unit group associated with the contract line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>uomscheduleid</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Unique identifier of the account with which the contract is associated.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Unique identifier of the account with which the contract is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>accountid</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Unique identifier for the contact associated with the contract line.  
First included in: service/ContractLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Unique identifier for the contact associated with the contract line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>contactid</td></tr></table>
