---
title: InvoiceLineTransaction - Common Data Model | Microsoft Docs
description: Transactions that are associated to an invoice line.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Invoice Line Detail

Transactions that are associated to an invoice line.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/InvoiceLineTransaction.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/InvoiceLineTransaction  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[ownerId](#ownerId)|Owner Id|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[invoiceLineTransactionId](#invoiceLineTransactionId)|Shows the entity instances.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[stateCode](#stateCode)|Status of the Invoice Line Detail|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[stateCode_display](#stateCode_display)||<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[statusCode](#statusCode)|Reason for the status of the Invoice Line Detail|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[statusCode_display](#statusCode_display)||<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[description](#description)|Type a description of the Invoice line transaction.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[accountCustomer](#accountCustomer)|Select the customer who this invoice will be sent to.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[accountingDate](#accountingDate)||<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[accountVendor](#accountVendor)||<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[amount](#amount)|Enter the amount on the transaction.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Shows the currency associated with the entity.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[amountBase](#amountBase)|Value of the Amount in base currency.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[amountMethod](#amountMethod)|Select the name of the amount calculation method.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[amountMethod_display](#amountMethod_display)||<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[basisAmount](#basisAmount)||<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[basisAmountBase](#basisAmountBase)|Value of the Basis Amount in base currency.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[basisPrice](#basisPrice)||<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[basisPriceBase](#basisPriceBase)|Value of the Basis Price in base currency.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[basisQuantity](#basisQuantity)||<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[billingType](#billingType)|Select whether this transaction will be charged to the customer or not. Only chargeable transactions will add to the invoice total|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[billingType_display](#billingType_display)||<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[bookableResource](#bookableResource)|Shows the resource.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[contactCustomer](#contactCustomer)|Select the customer who this invoice will be sent to.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[contactVendor](#contactVendor)||<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[contractingUnit](#contractingUnit)|Select the organizational unit in charge of the related contract.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[correction](#correction)|Indicates if this transaction is correcting a previous transaction.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[customerType](#customerType)|Select whether the customer was a account or a contact|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[customerType_display](#customerType_display)||<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[documentDate](#documentDate)|Enter the date on which this invoice line detail was sent to the customer|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[endDateTime](#endDateTime)|Date of invoiced transaction|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[exchangeRateDate](#exchangeRateDate)||<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[externalDescription](#externalDescription)|The external description of the invoice line detail|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[invoice](#invoice)|The invoice to which this invoice line detail belongs.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[invoiceLine](#invoiceLine)|(Deprecated) Shows the invoice line that this invoice line transaction is associated to.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[invoiceLineId](#invoiceLineId)|Unique identifier for Invoice Line associated with Invoice Line Detail.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[originalInvoiceLineDetail](#originalInvoiceLineDetail)|The original transaction that is being corrected if this is a correction transaction.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[percent](#percent)|Relevant when amount calculation method on the invoice line transaction is "Multiply basis amount by percent"|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[previousAmount](#previousAmount)|Amount that was previously invoiced if this is a correction.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[previousamountBase](#previousamountBase)|Value of the Previous Amount in base currency.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[price](#price)|Enter the price of the transaction.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[priceBase](#priceBase)|Value of the Price in base currency.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[priceList](#priceList)|Select the price list used for defaulting price on this transaction.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[product](#product)|Select the product on this invoice line transaction.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[project](#project)|Select the name of the project on which this transaction was created.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[quantity](#quantity)|Enter the quantity of the transaction.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[resourceCategory](#resourceCategory)|Select the role that the user resource who logged this transaction worked as.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[resourceOrganizationalUnitId](#resourceOrganizationalUnitId)|Select the organizational unit at the time the entry was registered of the resource who performed the work.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[salesContract](#salesContract)|Select the name of the project contract that this invoice belongs to.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[salesContractLine](#salesContractLine)|(Deprecated) Shows the ID of the project contract line for this invoice line|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[salesContractLineId](#salesContractLineId)|Unique identifier for Order Line associated with Invoice Line Detail.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[startDateTime](#startDateTime)|Enter the start date of the transaction.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[task](#task)|Select the name of the project task for which this transaction was created.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[transactionCategory](#transactionCategory)|Select the category of the transaction.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[transactionClassification](#transactionClassification)|Transaction classification of the invoice line|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[transactionClassification_display](#transactionClassification_display)||<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[transactionTypeCode](#transactionTypeCode)|Transaction type of the invoice line|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[transactionTypeCode_display](#transactionTypeCode_display)||<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[unit](#unit)|Select the unit of the transaction quantity.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[unitSchedule](#unitSchedule)|Select the unit group of the invoice line transaction.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[vendorType](#vendorType)||<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[vendorType_display](#vendorType_display)||<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[invoiceAmount](#invoiceAmount)|Amount to be invoiced. This is the line amount less the previously invoiced amount when this is a correction.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|
|[invoiceamountBase](#invoiceamountBase)|Value of the Invoice Amount in base currency.|<a href="InvoiceLineTransaction.md" target="_blank">projectServiceAutomation/InvoiceLineTransaction</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#invoiceLineTransactionId name="invoiceLineTransactionId">invoiceLineTransactionId</a>

Shows the entity instances.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Line Detail</td></tr><tr><td>description</td><td>Shows the entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_invoicelinetransactionid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Invoice Line Detail  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Invoice Line Detail</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Invoice Line Detail  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Invoice Line Detail</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#description name="description">description</a>

Type a description of the Invoice line transaction.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type a description of the Invoice line transaction.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_description</td></tr></table>

### <a href=#accountCustomer name="accountCustomer">accountCustomer</a>

Select the customer who this invoice will be sent to.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>Select the customer who this invoice will be sent to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_accountcustomer</td></tr></table>

### <a href=#accountingDate name="accountingDate">accountingDate</a>

First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accounting Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_accountingdate</td></tr></table>

### <a href=#accountVendor name="accountVendor">accountVendor</a>

First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_accountvendor</td></tr></table>

### <a href=#amount name="amount">amount</a>

Enter the amount on the transaction.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount</td></tr><tr><td>description</td><td>Enter the amount on the transaction.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Shows the currency associated with the entity.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Shows the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amountBase name="amountBase">amountBase</a>

Value of the Amount in base currency.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base)</td></tr><tr><td>description</td><td>Value of the Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amount_base</td></tr></table>

### <a href=#amountMethod name="amountMethod">amountMethod</a>

Select the name of the amount calculation method.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Method</td></tr><tr><td>description</td><td>Select the name of the amount calculation method.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_amountmethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Multiply Quantity By Price</td><td>192350000</td></tr><tr><td>en</td><td>Fixed Price</td><td>192350001</td></tr><tr><td>en</td><td>Multiply Basis Quantity By Price</td><td>192350002</td></tr><tr><td>en</td><td>Multiply Basis Amount By Percent</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#amountMethod_display name="amountMethod_display">amountMethod_display</a>

First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#basisAmount name="basisAmount">basisAmount</a>

First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Amount</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisamount</td></tr></table>

### <a href=#basisAmountBase name="basisAmountBase">basisAmountBase</a>

Value of the Basis Amount in base currency.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Amount (Base)</td></tr><tr><td>description</td><td>Value of the Basis Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisamount_base</td></tr></table>

### <a href=#basisPrice name="basisPrice">basisPrice</a>

First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Price</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisprice</td></tr></table>

### <a href=#basisPriceBase name="basisPriceBase">basisPriceBase</a>

Value of the Basis Price in base currency.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Price (Base)</td></tr><tr><td>description</td><td>Value of the Basis Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisprice_base</td></tr></table>

### <a href=#basisQuantity name="basisQuantity">basisQuantity</a>

First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Basis Quantity</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_basisquantity</td></tr></table>

### <a href=#billingType name="billingType">billingType</a>

Select whether this transaction will be charged to the customer or not. Only chargeable transactions will add to the invoice total  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing Type</td></tr><tr><td>description</td><td>Select whether this transaction will be charged to the customer or not. Only chargeable transactions will add to the invoice total</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_billingtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Non Chargeable</td><td>192350000</td></tr><tr><td>en</td><td>Chargeable</td><td>192350001</td></tr><tr><td>en</td><td>Complimentary</td><td>192350002</td></tr><tr><td>en</td><td>Not Available</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#billingType_display name="billingType_display">billingType_display</a>

First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#bookableResource name="bookableResource">bookableResource</a>

Shows the resource.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bookable Resource</td></tr><tr><td>description</td><td>Shows the resource.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_bookableresource</td></tr></table>

### <a href=#contactCustomer name="contactCustomer">contactCustomer</a>

Select the customer who this invoice will be sent to.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>Select the customer who this invoice will be sent to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contactcustomer</td></tr></table>

### <a href=#contactVendor name="contactVendor">contactVendor</a>

First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contactvendor</td></tr></table>

### <a href=#contractingUnit name="contractingUnit">contractingUnit</a>

Select the organizational unit in charge of the related contract.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contracting Unit</td></tr><tr><td>description</td><td>Select the organizational unit in charge of the related contract.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contractorganizationalunitid</td></tr></table>

### <a href=#correction name="correction">correction</a>

Indicates if this transaction is correcting a previous transaction.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Correction</td></tr><tr><td>description</td><td>Indicates if this transaction is correcting a previous transaction.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_correction</td></tr></table>

### <a href=#customerType name="customerType">customerType</a>

Select whether the customer was a account or a contact  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>Select whether the customer was a account or a contact</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_customertype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Account</td><td>192350001</td></tr><tr><td>en</td><td>Contact</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#customerType_display name="customerType_display">customerType_display</a>

First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#documentDate name="documentDate">documentDate</a>

Enter the date on which this invoice line detail was sent to the customer  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document Date</td></tr><tr><td>description</td><td>Enter the date on which this invoice line detail was sent to the customer</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_documentdate</td></tr></table>

### <a href=#endDateTime name="endDateTime">endDateTime</a>

Date of invoiced transaction  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date/Time</td></tr><tr><td>description</td><td>Date of invoiced transaction</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_enddatetime</td></tr></table>

### <a href=#exchangeRateDate name="exchangeRateDate">exchangeRateDate</a>

First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate Date</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_exchangeratedate</td></tr></table>

### <a href=#externalDescription name="externalDescription">externalDescription</a>

The external description of the invoice line detail  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External Description</td></tr><tr><td>description</td><td>The external description of the invoice line detail</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_externaldescription</td></tr></table>

### <a href=#invoice name="invoice">invoice</a>

The invoice to which this invoice line detail belongs.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice</td></tr><tr><td>description</td><td>The invoice to which this invoice line detail belongs.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_invoice</td></tr></table>

### <a href=#invoiceLine name="invoiceLine">invoiceLine</a>

(Deprecated) Shows the invoice line that this invoice line transaction is associated to.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>(Deprecated) Invoice Line</td></tr><tr><td>description</td><td>(Deprecated) Shows the invoice line that this invoice line transaction is associated to.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_invoiceline</td></tr></table>

### <a href=#invoiceLineId name="invoiceLineId">invoiceLineId</a>

Unique identifier for Invoice Line associated with Invoice Line Detail.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Line</td></tr><tr><td>description</td><td>Unique identifier for Invoice Line associated with Invoice Line Detail.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_invoicelineid</td></tr></table>

### <a href=#originalInvoiceLineDetail name="originalInvoiceLineDetail">originalInvoiceLineDetail</a>

The original transaction that is being corrected if this is a correction transaction.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Original Invoice Line Detail</td></tr><tr><td>description</td><td>The original transaction that is being corrected if this is a correction transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_originalinvoicelinedetail</td></tr></table>

### <a href=#percent name="percent">percent</a>

Relevant when amount calculation method on the invoice line transaction is "Multiply basis amount by percent"  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percent</td></tr><tr><td>description</td><td>Relevant when amount calculation method on the invoice line transaction is "Multiply basis amount by percent"</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_percent</td></tr></table>

### <a href=#previousAmount name="previousAmount">previousAmount</a>

Amount that was previously invoiced if this is a correction.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Previous Amount</td></tr><tr><td>description</td><td>Amount that was previously invoiced if this is a correction.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_previousamount</td></tr></table>

### <a href=#previousamountBase name="previousamountBase">previousamountBase</a>

Value of the Previous Amount in base currency.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Previous Amount (Base)</td></tr><tr><td>description</td><td>Value of the Previous Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_previousamount_base</td></tr></table>

### <a href=#price name="price">price</a>

Enter the price of the transaction.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price</td></tr><tr><td>description</td><td>Enter the price of the transaction.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_price</td></tr></table>

### <a href=#priceBase name="priceBase">priceBase</a>

Value of the Price in base currency.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price (Base)</td></tr><tr><td>description</td><td>Value of the Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_price_base</td></tr></table>

### <a href=#priceList name="priceList">priceList</a>

Select the price list used for defaulting price on this transaction.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price List</td></tr><tr><td>description</td><td>Select the price list used for defaulting price on this transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_pricelist</td></tr></table>

### <a href=#product name="product">product</a>

Select the product on this invoice line transaction.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product</td></tr><tr><td>description</td><td>Select the product on this invoice line transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_product</td></tr></table>

### <a href=#project name="project">project</a>

Select the name of the project on which this transaction was created.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project</td></tr><tr><td>description</td><td>Select the name of the project on which this transaction was created.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_project</td></tr></table>

### <a href=#quantity name="quantity">quantity</a>

Enter the quantity of the transaction.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity</td></tr><tr><td>description</td><td>Enter the quantity of the transaction.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_quantity</td></tr></table>

### <a href=#resourceCategory name="resourceCategory">resourceCategory</a>

Select the role that the user resource who logged this transaction worked as.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Role</td></tr><tr><td>description</td><td>Select the role that the user resource who logged this transaction worked as.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourcecategory</td></tr></table>

### <a href=#resourceOrganizationalUnitId name="resourceOrganizationalUnitId">resourceOrganizationalUnitId</a>

Select the organizational unit at the time the entry was registered of the resource who performed the work.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resourcing Unit</td></tr><tr><td>description</td><td>Select the organizational unit at the time the entry was registered of the resource who performed the work.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_resourceorganizationalunitid</td></tr></table>

### <a href=#salesContract name="salesContract">salesContract</a>

Select the name of the project contract that this invoice belongs to.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Contract</td></tr><tr><td>description</td><td>Select the name of the project contract that this invoice belongs to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salescontract</td></tr></table>

### <a href=#salesContractLine name="salesContractLine">salesContractLine</a>

(Deprecated) Shows the ID of the project contract line for this invoice line  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>(Deprecated) Project Contract Line</td></tr><tr><td>description</td><td>(Deprecated) Shows the ID of the project contract line for this invoice line</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salescontractline</td></tr></table>

### <a href=#salesContractLineId name="salesContractLineId">salesContractLineId</a>

Unique identifier for Order Line associated with Invoice Line Detail.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project Contract Line</td></tr><tr><td>description</td><td>Unique identifier for Order Line associated with Invoice Line Detail.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_salescontractlineid</td></tr></table>

### <a href=#startDateTime name="startDateTime">startDateTime</a>

Enter the start date of the transaction.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Enter the start date of the transaction.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_startdatetime</td></tr></table>

### <a href=#task name="task">task</a>

Select the name of the project task for which this transaction was created.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Task</td></tr><tr><td>description</td><td>Select the name of the project task for which this transaction was created.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_task</td></tr></table>

### <a href=#transactionCategory name="transactionCategory">transactionCategory</a>

Select the category of the transaction.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Category</td></tr><tr><td>description</td><td>Select the category of the transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactioncategory</td></tr></table>

### <a href=#transactionClassification name="transactionClassification">transactionClassification</a>

Transaction classification of the invoice line  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Class</td></tr><tr><td>description</td><td>Transaction classification of the invoice line</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactionclassification</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Time</td><td>192350000</td></tr><tr><td>en</td><td>Expense</td><td>192350001</td></tr><tr><td>en</td><td>Material</td><td>192350002</td></tr><tr><td>en</td><td>Milestone</td><td>192350003</td></tr><tr><td>en</td><td>Fee</td><td>192350004</td></tr><tr><td>en</td><td>Tax</td><td>690970002</td></tr></table></td></tr></table>

### <a href=#transactionClassification_display name="transactionClassification_display">transactionClassification_display</a>

First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionTypeCode name="transactionTypeCode">transactionTypeCode</a>

Transaction type of the invoice line  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Type</td></tr><tr><td>description</td><td>Transaction type of the invoice line</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactiontypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Cost</td><td>192350000</td></tr><tr><td>en</td><td>Project Contract</td><td>192350004</td></tr><tr><td>en</td><td>Unbilled Sales</td><td>192350005</td></tr><tr><td>en</td><td>Billed Sales</td><td>192350006</td></tr><tr><td>en</td><td>Resourcing Unit Cost</td><td>192350007</td></tr><tr><td>en</td><td>Inter-Organizational Sales</td><td>192350008</td></tr></table></td></tr></table>

### <a href=#transactionTypeCode_display name="transactionTypeCode_display">transactionTypeCode_display</a>

First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#unit name="unit">unit</a>

Select the unit of the transaction quantity.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit</td></tr><tr><td>description</td><td>Select the unit of the transaction quantity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_unit</td></tr></table>

### <a href=#unitSchedule name="unitSchedule">unitSchedule</a>

Select the unit group of the invoice line transaction.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit Schedule</td></tr><tr><td>description</td><td>Select the unit group of the invoice line transaction.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_unitschedule</td></tr></table>

### <a href=#vendorType name="vendorType">vendorType</a>

First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_vendortype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Account</td><td>192350001</td></tr><tr><td>en</td><td>Contact</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#vendorType_display name="vendorType_display">vendorType_display</a>

First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#invoiceAmount name="invoiceAmount">invoiceAmount</a>

Amount to be invoiced. This is the line amount less the previously invoiced amount when this is a correction.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Amount</td></tr><tr><td>description</td><td>Amount to be invoiced. This is the line amount less the previously invoiced amount when this is a correction.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_invoiceamount</td></tr></table>

### <a href=#invoiceamountBase name="invoiceamountBase">invoiceamountBase</a>

Value of the Invoice Amount in base currency.  
First included in: projectServiceAutomation/InvoiceLineTransaction (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Amount (Base)</td></tr><tr><td>description</td><td>Value of the Invoice Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_invoiceamount_base</td></tr></table>
