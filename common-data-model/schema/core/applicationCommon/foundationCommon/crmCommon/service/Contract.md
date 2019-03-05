---
title: Contract - Common Data Model | Microsoft Docs
description: Agreement to provide customer service during a specified amount of time or number of cases.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Contract

Agreement to provide customer service during a specified amount of time or number of cases.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/service/Contract.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/service/Contract  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[ownerId](#ownerId)|Owner Id|<a href="Contract.md" target="_blank">service/Contract</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="Contract.md" target="_blank">service/Contract</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Contract.md" target="_blank">service/Contract</a>|
|[contractId](#contractId)|Unique identifier of the contract.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[emailAddress](#emailAddress)|The primary email address for the entity.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[title](#title)|Type a title or name for the contract that indicates the purpose of the contract.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[activeOn](#activeOn)|Enter the date when the contract becomes active.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[allotmentTypeCode](#allotmentTypeCode)|Type of allotment that the contract supports.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[allotmentTypeCode_display](#allotmentTypeCode_display)||<a href="Contract.md" target="_blank">service/Contract</a>|
|[billingCustomerIdType](#billingCustomerIdType)|The type of billing customer, either Account or Contact.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[billingCustomerId](#billingCustomerId)|Select the customer account or contact to which the contract should be billed to provide a quick link to address and other customer details.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[billingEndOn](#billingEndOn)|Enter the end date for the contract's billing period to indicate the period for which the customer must pay for a service.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[billingFrequencyCode](#billingFrequencyCode)|Select the billing schedule of the contract to indicate how often the customer should be invoiced.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[billingFrequencyCode_display](#billingFrequencyCode_display)||<a href="Contract.md" target="_blank">service/Contract</a>|
|[billingStartOn](#billingStartOn)|Enter the start date for the contract's billing period to indicate the period for which the customer must pay for a service. This defaults to the same date that is selected in the Contract Start Date field.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[billToAddress](#billToAddress)|Choose which address to send the invoice to.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[cancelOn](#cancelOn)|Shows the date and time when the contract was canceled.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[contractLanguage](#contractLanguage)|Type additional information about the contract, such as the products or services provided to the customer.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[contractNumber](#contractNumber)|Shows the number for the contract for customer reference and searching capabilities. You cannot modify this number.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[contractServiceLevelCode](#contractServiceLevelCode)|Select the level of service that should be provided for the contract based on your company's definition of bronze, silver, or gold.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[contractServiceLevelCode_display](#contractServiceLevelCode_display)||<a href="Contract.md" target="_blank">service/Contract</a>|
|[contractTemplateAbbreviation](#contractTemplateAbbreviation)|Shows the abbreviation of the contract template selected when the contract is created.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[contractTemplateId](#contractTemplateId)|Choose the contract template that should be used to determine the terms of the contract, such as allotment type, available hours, and billing frequency.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[customerIdType](#customerIdType)|The type of customer, either Account or Contact.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[customerId](#customerId)|The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[duration](#duration)|Shows for the duration of the contract, in days, based on the contract start and end dates.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[effectivityCalendar](#effectivityCalendar)|Days of the week and times during which customer service support is available for the duration of the contract.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[expiresOn](#expiresOn)|Enter the date when the contract expires.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[netPrice](#netPrice)|Shows the total charge to the customer for the service contract, calculated as the sum of values in the Net field for each existing contract line related to the contract.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[netPriceBase](#netPriceBase)|Value of the Net Price in base currency.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[originatingContract](#originatingContract)|Choose the original contract that this contract was created from. This information is used to track renewal history.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[serviceAddress](#serviceAddress)|Choose the address for the customer account or contact where the services are provided.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[stateCode](#stateCode)|Shows whether the contract is in draft, invoiced, active, on hold, canceled, or expired. You can edit only the contracts that are in draft status.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[stateCode_display](#stateCode_display)||<a href="Contract.md" target="_blank">service/Contract</a>|
|[statusCode](#statusCode)|Select the contract's status.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[statusCode_display](#statusCode_display)||<a href="Contract.md" target="_blank">service/Contract</a>|
|[totalDiscount](#totalDiscount)|Shows the total discount applied to the contract's service charges, calculated as the sum of values in the Discount fields for each existing contract line related to the contract.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[totalDiscountBase](#totalDiscountBase)|Value of the Total Discount in base currency.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[totalPrice](#totalPrice)|Shows the total service charge for the contract, before any discounts are credited. This is calculated as the sum of values in the Total Price field for each existing contract line related to the contract.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[totalPriceBase](#totalPriceBase)|Value of the Total Price in base currency.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[useDiscountAsPercentage](#useDiscountAsPercentage)|Select whether the discounts entered on contract lines for this contract should be entered as a percentage or a fixed dollar value.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[entityImageId](#entityImageId)||<a href="Contract.md" target="_blank">service/Contract</a>|
|[accountId](#accountId)|Unique identifier of the account with which the contract is associated.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[billingAccountId](#billingAccountId)|Unique identifier of the account to which the contract is to be billed.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[billingContactId](#billingContactId)|Unique identifier of the contact to whom the contract is to be billed.|<a href="Contract.md" target="_blank">service/Contract</a>|
|[contactId](#contactId)|Unique identifier of the contact specified for the contract.|<a href="Contract.md" target="_blank">service/Contract</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#contractId name="contractId">contractId</a>

Unique identifier of the contract.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract</td></tr><tr><td>description</td><td>Unique identifier of the contract.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>contractid</td></tr></table>

### <a href=#emailAddress name="emailAddress">emailAddress</a>

The primary email address for the entity.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Address</td></tr><tr><td>description</td><td>The primary email address for the entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress</td></tr></table>

### <a href=#title name="title">title</a>

Type a title or name for the contract that indicates the purpose of the contract.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract Name</td></tr><tr><td>description</td><td>Type a title or name for the contract that indicates the purpose of the contract.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>title</td></tr></table>

### <a href=#activeOn name="activeOn">activeOn</a>

Enter the date when the contract becomes active.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract Start Date</td></tr><tr><td>description</td><td>Enter the date when the contract becomes active.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>activeon</td></tr></table>

### <a href=#allotmentTypeCode name="allotmentTypeCode">allotmentTypeCode</a>

Type of allotment that the contract supports.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allotment Type</td></tr><tr><td>description</td><td>Type of allotment that the contract supports.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>allotmenttypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Number of Cases</td><td>1</td></tr><tr><td>en</td><td>Time</td><td>2</td></tr><tr><td>en</td><td>Coverage Dates</td><td>3</td></tr></table></td></tr></table>

### <a href=#allotmentTypeCode_display name="allotmentTypeCode_display">allotmentTypeCode_display</a>

First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#billingCustomerIdType name="billingCustomerIdType">billingCustomerIdType</a>

The type of billing customer, either Account or Contact.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing Customer Type</td></tr><tr><td>description</td><td>The type of billing customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>billingcustomeridtype</td></tr></table>

### <a href=#billingCustomerId name="billingCustomerId">billingCustomerId</a>

Select the customer account or contact to which the contract should be billed to provide a quick link to address and other customer details.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Customer</td></tr><tr><td>description</td><td>Select the customer account or contact to which the contract should be billed to provide a quick link to address and other customer details.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billingcustomerid</td></tr></table>

### <a href=#billingEndOn name="billingEndOn">billingEndOn</a>

Enter the end date for the contract's billing period to indicate the period for which the customer must pay for a service.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing End Date</td></tr><tr><td>description</td><td>Enter the end date for the contract's billing period to indicate the period for which the customer must pay for a service.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billingendon</td></tr></table>

### <a href=#billingFrequencyCode name="billingFrequencyCode">billingFrequencyCode</a>

Select the billing schedule of the contract to indicate how often the customer should be invoiced.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing Frequency</td></tr><tr><td>description</td><td>Select the billing schedule of the contract to indicate how often the customer should be invoiced.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billingfrequencycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Monthly</td><td>1</td></tr><tr><td>en</td><td>Bimonthly</td><td>2</td></tr><tr><td>en</td><td>Quarterly</td><td>3</td></tr><tr><td>en</td><td>Semiannually</td><td>4</td></tr><tr><td>en</td><td>Annually</td><td>5</td></tr></table></td></tr></table>

### <a href=#billingFrequencyCode_display name="billingFrequencyCode_display">billingFrequencyCode_display</a>

First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#billingStartOn name="billingStartOn">billingStartOn</a>

Enter the start date for the contract's billing period to indicate the period for which the customer must pay for a service. This defaults to the same date that is selected in the Contract Start Date field.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing Start Date</td></tr><tr><td>description</td><td>Enter the start date for the contract's billing period to indicate the period for which the customer must pay for a service. This defaults to the same date that is selected in the Contract Start Date field.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billingstarton</td></tr></table>

### <a href=#billToAddress name="billToAddress">billToAddress</a>

Choose which address to send the invoice to.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Address</td></tr><tr><td>description</td><td>Choose which address to send the invoice to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billtoaddress</td></tr></table>

### <a href=#cancelOn name="cancelOn">cancelOn</a>

Shows the date and time when the contract was canceled.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cancellation Date</td></tr><tr><td>description</td><td>Shows the date and time when the contract was canceled.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>cancelon</td></tr></table>

### <a href=#contractLanguage name="contractLanguage">contractLanguage</a>

Type additional information about the contract, such as the products or services provided to the customer.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information about the contract, such as the products or services provided to the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>contractlanguage</td></tr></table>

### <a href=#contractNumber name="contractNumber">contractNumber</a>

Shows the number for the contract for customer reference and searching capabilities. You cannot modify this number.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract ID</td></tr><tr><td>description</td><td>Shows the number for the contract for customer reference and searching capabilities. You cannot modify this number.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>contractnumber</td></tr></table>

### <a href=#contractServiceLevelCode name="contractServiceLevelCode">contractServiceLevelCode</a>

Select the level of service that should be provided for the contract based on your company's definition of bronze, silver, or gold.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Service Level</td></tr><tr><td>description</td><td>Select the level of service that should be provided for the contract based on your company's definition of bronze, silver, or gold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>contractservicelevelcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Gold</td><td>1</td></tr><tr><td>en</td><td>Silver</td><td>2</td></tr><tr><td>en</td><td>Bronze</td><td>3</td></tr></table></td></tr></table>

### <a href=#contractServiceLevelCode_display name="contractServiceLevelCode_display">contractServiceLevelCode_display</a>

First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#contractTemplateAbbreviation name="contractTemplateAbbreviation">contractTemplateAbbreviation</a>

Shows the abbreviation of the contract template selected when the contract is created.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Template Abbreviation</td></tr><tr><td>description</td><td>Shows the abbreviation of the contract template selected when the contract is created.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>sourceName</td><td>contracttemplateabbreviation</td></tr></table>

### <a href=#contractTemplateId name="contractTemplateId">contractTemplateId</a>

Choose the contract template that should be used to determine the terms of the contract, such as allotment type, available hours, and billing frequency.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract Template</td></tr><tr><td>description</td><td>Choose the contract template that should be used to determine the terms of the contract, such as allotment type, available hours, and billing frequency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>contracttemplateid</td></tr></table>

### <a href=#customerIdType name="customerIdType">customerIdType</a>

The type of customer, either Account or Contact.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>The type of customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>customeridtype</td></tr></table>

### <a href=#customerId name="customerId">customerId</a>

The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerid</td></tr></table>

### <a href=#duration name="duration">duration</a>

Shows for the duration of the contract, in days, based on the contract start and end dates.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Duration</td></tr><tr><td>description</td><td>Shows for the duration of the contract, in days, based on the contract start and end dates.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>duration</td></tr></table>

### <a href=#effectivityCalendar name="effectivityCalendar">effectivityCalendar</a>

Days of the week and times during which customer service support is available for the duration of the contract.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Support Calendar</td></tr><tr><td>description</td><td>Days of the week and times during which customer service support is available for the duration of the contract.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>168</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>effectivitycalendar</td></tr></table>

### <a href=#expiresOn name="expiresOn">expiresOn</a>

Enter the date when the contract expires.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract End Date</td></tr><tr><td>description</td><td>Enter the date when the contract expires.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>expireson</td></tr></table>

### <a href=#netPrice name="netPrice">netPrice</a>

Shows the total charge to the customer for the service contract, calculated as the sum of values in the Net field for each existing contract line related to the contract.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Net Price</td></tr><tr><td>description</td><td>Shows the total charge to the customer for the service contract, calculated as the sum of values in the Net field for each existing contract line related to the contract.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>netprice</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#netPriceBase name="netPriceBase">netPriceBase</a>

Value of the Net Price in base currency.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Net Price (Base)</td></tr><tr><td>description</td><td>Value of the Net Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>netprice_base</td></tr></table>

### <a href=#originatingContract name="originatingContract">originatingContract</a>

Choose the original contract that this contract was created from. This information is used to track renewal history.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Originating Contract</td></tr><tr><td>description</td><td>Choose the original contract that this contract was created from. This information is used to track renewal history.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>originatingcontract</td></tr></table>

### <a href=#serviceAddress name="serviceAddress">serviceAddress</a>

Choose the address for the customer account or contact where the services are provided.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract Address</td></tr><tr><td>description</td><td>Choose the address for the customer account or contact where the services are provided.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>serviceaddress</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the contract is in draft, invoiced, active, on hold, canceled, or expired. You can edit only the contracts that are in draft status.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the contract is in draft, invoiced, active, on hold, canceled, or expired. You can edit only the contracts that are in draft status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Draft</td><td>0</td></tr><tr><td>en</td><td>Invoiced</td><td>1</td></tr><tr><td>en</td><td>Active</td><td>2</td></tr><tr><td>en</td><td>On Hold</td><td>3</td></tr><tr><td>en</td><td>Canceled</td><td>4</td></tr><tr><td>en</td><td>Expired</td><td>5</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the contract's status.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the contract's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Draft</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Invoiced</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Active</td><td>3</td><td>2</td></tr><tr><td>en</td><td>On Hold</td><td>4</td><td>3</td></tr><tr><td>en</td><td>Canceled</td><td>5</td><td>4</td></tr><tr><td>en</td><td>Expired</td><td>6</td><td>5</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#totalDiscount name="totalDiscount">totalDiscount</a>

Shows the total discount applied to the contract's service charges, calculated as the sum of values in the Discount fields for each existing contract line related to the contract.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Discount</td></tr><tr><td>description</td><td>Shows the total discount applied to the contract's service charges, calculated as the sum of values in the Discount fields for each existing contract line related to the contract.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totaldiscount</td></tr></table>

### <a href=#totalDiscountBase name="totalDiscountBase">totalDiscountBase</a>

Value of the Total Discount in base currency.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Discount (Base)</td></tr><tr><td>description</td><td>Value of the Total Discount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totaldiscount_base</td></tr></table>

### <a href=#totalPrice name="totalPrice">totalPrice</a>

Shows the total service charge for the contract, before any discounts are credited. This is calculated as the sum of values in the Total Price field for each existing contract line related to the contract.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Price</td></tr><tr><td>description</td><td>Shows the total service charge for the contract, before any discounts are credited. This is calculated as the sum of values in the Total Price field for each existing contract line related to the contract.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalprice</td></tr></table>

### <a href=#totalPriceBase name="totalPriceBase">totalPriceBase</a>

Value of the Total Price in base currency.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Price (Base)</td></tr><tr><td>description</td><td>Value of the Total Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalprice_base</td></tr></table>

### <a href=#useDiscountAsPercentage name="useDiscountAsPercentage">useDiscountAsPercentage</a>

Select whether the discounts entered on contract lines for this contract should be entered as a percentage or a fixed dollar value.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount</td></tr><tr><td>description</td><td>Select whether the discounts entered on contract lines for this contract should be entered as a percentage or a fixed dollar value.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>usediscountaspercentage</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Unique identifier of the account with which the contract is associated.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Unique identifier of the account with which the contract is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>accountid</td></tr></table>

### <a href=#billingAccountId name="billingAccountId">billingAccountId</a>

Unique identifier of the account to which the contract is to be billed.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing Account</td></tr><tr><td>description</td><td>Unique identifier of the account to which the contract is to be billed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billingaccountid</td></tr></table>

### <a href=#billingContactId name="billingContactId">billingContactId</a>

Unique identifier of the contact to whom the contract is to be billed.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing Contact</td></tr><tr><td>description</td><td>Unique identifier of the contact to whom the contract is to be billed.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billingcontactid</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Unique identifier of the contact specified for the contract.  
First included in: service/Contract (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Unique identifier of the contact specified for the contract.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>contactid</td></tr></table>
