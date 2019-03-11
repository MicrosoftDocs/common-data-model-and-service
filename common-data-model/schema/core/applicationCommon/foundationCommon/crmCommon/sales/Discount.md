---
title: Discount - Common Data Model | Microsoft Docs
description: Price reduction made from the list price of a product or service based on the quantity purchased.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Discount

Price reduction made from the list price of a product or service based on the quantity purchased.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/sales/Discount.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/sales/Discount  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[discountId](#discountId)|Unique identifier of the discount.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[createdOn](#createdOn)|Date and time when the discount was created.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the discount.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[modifiedOn](#modifiedOn)|Date and time when the discount was last modified.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the discount.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the discount.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the discount.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[name](#name)|name|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[amount](#amount)|Amount of the discount, specified either as a percentage or as a monetary amount.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[amountBase](#amountBase)|Value of the Amount in base currency.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[discountTypeId](#discountTypeId)|Unique identifier of the discount list associated with the discount.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[highQuantity](#highQuantity)|Upper boundary for the quantity range to which a particular discount can be applied.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[isAmountType](#isAmountType)|Specifies whether the discount is specified as a monetary amount or a percentage.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[lowQuantity](#lowQuantity)|Lower boundary for the quantity range to which a particular discount is applied.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[organizationId](#organizationId)|Unique identifier of the organization associated with the discount.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[percentage](#percentage)|Percentage discount value.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[statusCode](#statusCode)|Select the discount's status.|<a href="Discount.md" target="_blank">sales/Discount</a>|
|[statusCode_display](#statusCode_display)||<a href="Discount.md" target="_blank">sales/Discount</a>|

### <a href=#discountId name="discountId">discountId</a>

Unique identifier of the discount.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount</td></tr><tr><td>description</td><td>Unique identifier of the discount.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>discountid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the discount was created.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the discount was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the discount.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the discount.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the discount was last modified.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the discount was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the discount.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the discount.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the discount.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the discount.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the discount.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the discount.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

name  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>name</td></tr><tr><td>description</td><td>name</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#amount name="amount">amount</a>

Amount of the discount, specified either as a percentage or as a monetary amount.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount</td></tr><tr><td>description</td><td>Amount of the discount, specified either as a percentage or as a monetary amount.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>amount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amountBase name="amountBase">amountBase</a>

Value of the Amount in base currency.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base)</td></tr><tr><td>description</td><td>Value of the Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>amount_base</td></tr></table>

### <a href=#discountTypeId name="discountTypeId">discountTypeId</a>

Unique identifier of the discount list associated with the discount.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount Type</td></tr><tr><td>description</td><td>Unique identifier of the discount list associated with the discount.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>discounttypeid</td></tr></table>

### <a href=#highQuantity name="highQuantity">highQuantity</a>

Upper boundary for the quantity range to which a particular discount can be applied.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Quantity</td></tr><tr><td>description</td><td>Upper boundary for the quantity range to which a particular discount can be applied.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-05</td></tr><tr><td>sourceName</td><td>highquantity</td></tr></table>

### <a href=#isAmountType name="isAmountType">isAmountType</a>

Specifies whether the discount is specified as a monetary amount or a percentage.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Type</td></tr><tr><td>description</td><td>Specifies whether the discount is specified as a monetary amount or a percentage.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isamounttype</td></tr></table>

### <a href=#lowQuantity name="lowQuantity">lowQuantity</a>

Lower boundary for the quantity range to which a particular discount is applied.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Begin Quantity</td></tr><tr><td>description</td><td>Lower boundary for the quantity range to which a particular discount is applied.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-05</td></tr><tr><td>sourceName</td><td>lowquantity</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization associated with the discount.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization </td></tr><tr><td>description</td><td>Unique identifier of the organization associated with the discount.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#percentage name="percentage">percentage</a>

Percentage discount value.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percentage</td></tr><tr><td>description</td><td>Percentage discount value.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>percentage</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the discount's status.  
First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the discount's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: sales/Discount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
