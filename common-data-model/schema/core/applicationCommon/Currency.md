---
title: Currency - Common Data Model | Microsoft Docs
description: Currency in which a financial transaction is carried out.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Currency

Currency in which a financial transaction is carried out.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/Currency.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /Currency  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[statusCode](#statusCode)|Reason for the status of the transaction currency.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[statusCode_display](#statusCode_display)||<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[modifiedOn](#modifiedOn)|Date and time when the transaction currency was last modified.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[stateCode](#stateCode)|Status of the transaction currency.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[stateCode_display](#stateCode_display)||<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[versionNumber](#versionNumber)|Version number of the transaction currency.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the transaction currency.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[createdOn](#createdOn)|Date and time when the transaction currency was created.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the transaction currency.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[exchangeRate](#exchangeRate)|Exchange rate between the transaction currency and the base currency.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[currencySymbol](#currencySymbol)|Symbol for the transaction currency.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[currencyName](#currencyName)|Name of the transaction currency.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the transaction currency.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[ISOCurrencyCode](#ISOCurrencyCode)|ISO currency code for the transaction currency.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[organizationId](#organizationId)|Unique identifier of the organization associated with the transaction currency.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[currencyPrecision](#currencyPrecision)|Number of decimal places that can be used for currency.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the transactioncurrency.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the transactioncurrency.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|
|[entityImageId](#entityImageId)|For internal use only.|<a href="Currency.md" target="_blank">applicationCommon/Currency</a>|

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the transaction currency.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the transaction currency.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the transaction currency was last modified.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the transaction currency was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the transaction currency.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the transaction currency.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version number of the transaction currency.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version number of the transaction currency.</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the transaction currency.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the transaction currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the transaction currency was created.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the transaction currency was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the transaction currency.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Currency</td></tr><tr><td>description</td><td>Unique identifier of the transaction currency.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate between the transaction currency and the base currency.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate between the transaction currency and the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#currencySymbol name="currencySymbol">currencySymbol</a>

Symbol for the transaction currency.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency Symbol</td></tr><tr><td>description</td><td>Symbol for the transaction currency.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>10</td></tr><tr><td>sourceName</td><td>currencysymbol</td></tr></table>

### <a href=#currencyName name="currencyName">currencyName</a>

Name of the transaction currency.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency Name</td></tr><tr><td>description</td><td>Name of the transaction currency.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>currencyname</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the transaction currency.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the transaction currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#ISOCurrencyCode name="ISOCurrencyCode">ISOCurrencyCode</a>

ISO currency code for the transaction currency.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency Code</td></tr><tr><td>description</td><td>ISO currency code for the transaction currency.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>5</td></tr><tr><td>sourceName</td><td>isocurrencycode</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization associated with the transaction currency.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>Unique identifier of the organization associated with the transaction currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#currencyPrecision name="currencyPrecision">currencyPrecision</a>

Number of decimal places that can be used for currency.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency Precision</td></tr><tr><td>description</td><td>Number of decimal places that can be used for currency.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>4</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>currencyprecision</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the transactioncurrency.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the transactioncurrency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the transactioncurrency.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the transactioncurrency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

For internal use only.  
First included in: applicationCommon/Currency (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entity Image Id</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>
