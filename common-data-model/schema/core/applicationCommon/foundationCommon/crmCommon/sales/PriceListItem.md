---
title: PriceListItem - Common Data Model | Microsoft Docs
description: This describes the PriceListItem entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/5/2019
ms.author: nebanfic
---

# Price List Item

Information about how to price a product in the specified price level, including pricing method, rounding option, and discount type based on a specified product unit.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/sales/PriceListItem.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/foundationCommon/PriceListItem](../../PriceListItem.md "/core/applicationCommon/foundationCommon/PriceListItem.cdm.json/PriceListItem")  
- /foundationCommon/crmCommon/sales/PriceListItem  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[productPriceLevelId](#productPriceLevelId)|Unique identifier of the price list.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[createdOn](#createdOn)|Date and time when the price list was created.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the price list.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[modifiedOn](#modifiedOn)|Date and time when the price list was last modified.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the price list.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[amount](#amount)|Monetary amount for the price list.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[amountBase](#amountBase)|Value of the Amount in base currency.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[organizationId](#organizationId)|Unique identifier of the organization associated with the price list.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[percentage](#percentage)|Percentage for the price list.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[priceLevelId](#priceLevelId)|Unique identifier of the price level associated with this price list.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[pricingMethodCode](#pricingMethodCode)|Pricing method applied to the price list.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[pricingMethodCode_display](#pricingMethodCode_display)||<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[productId](#productId)|Product associated with the price list.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[productNumber](#productNumber)|User-defined product number.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[quantitySellingCode](#quantitySellingCode)|Quantity of the product that must be sold for a given price level.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[quantitySellingCode_display](#quantitySellingCode_display)||<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[roundingOptionAmount](#roundingOptionAmount)|Rounding option amount for the price list.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[roundingOptionAmountBase](#roundingOptionAmountBase)|Value of the Rounding Amount in base currency.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[roundingOptionCode](#roundingOptionCode)|Option for rounding the price list.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[roundingOptionCode_display](#roundingOptionCode_display)||<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[roundingPolicyCode](#roundingPolicyCode)|Policy for rounding the price list.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[roundingPolicyCode_display](#roundingPolicyCode_display)||<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[uoMId](#uoMId)|Unique identifier of the unit for the price list.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[uoMScheduleId](#uoMScheduleId)|Unique identifier of the unit schedule for the price list.|<a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>|
|[discountTypeId](#discountTypeId)|Unique identifier of the discount list associated with the price list.|<a href="PriceListItem.md" target="_blank">sales/PriceListItem</a>|

### <a href=#productPriceLevelId name="productPriceLevelId">productPriceLevelId</a>

Unique identifier of the price list.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product Price List</td></tr><tr><td>description</td><td>Unique identifier of the price list.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>productpricelevelid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the price list was created.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the price list was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the price list.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the price list.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the price list was last modified.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the price list was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the price list.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the price list.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#amount name="amount">amount</a>

Monetary amount for the price list.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount</td></tr><tr><td>description</td><td>Monetary amount for the price list.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>amount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#amountBase name="amountBase">amountBase</a>

Value of the Amount in base currency.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base)</td></tr><tr><td>description</td><td>Value of the Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>amount_base</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization associated with the price list.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>Unique identifier of the organization associated with the price list.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#percentage name="percentage">percentage</a>

Percentage for the price list.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percentage</td></tr><tr><td>description</td><td>Percentage for the price list.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>percentage</td></tr></table>

### <a href=#priceLevelId name="priceLevelId">priceLevelId</a>

Unique identifier of the price level associated with this price list.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price List</td></tr><tr><td>description</td><td>Unique identifier of the price level associated with this price list.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>pricelevelid</td></tr></table>

### <a href=#pricingMethodCode name="pricingMethodCode">pricingMethodCode</a>

Pricing method applied to the price list.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pricing Method</td></tr><tr><td>description</td><td>Pricing method applied to the price list.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>pricingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Currency Amount</td><td>1</td></tr><tr><td>en</td><td>Percent of List</td><td>2</td></tr><tr><td>en</td><td>Percent Markup - Current Cost</td><td>3</td></tr><tr><td>en</td><td>Percent Margin - Current Cost</td><td>4</td></tr><tr><td>en</td><td>Percent Markup - Standard Cost</td><td>5</td></tr><tr><td>en</td><td>Percent Margin - Standard Cost</td><td>6</td></tr></table></td></tr></table>

### <a href=#pricingMethodCode_display name="pricingMethodCode_display">pricingMethodCode_display</a>

First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#productId name="productId">productId</a>

Product associated with the price list.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product</td></tr><tr><td>description</td><td>Product associated with the price list.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>productid</td></tr></table>

### <a href=#productNumber name="productNumber">productNumber</a>

User-defined product number.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product ID</td></tr><tr><td>description</td><td>User-defined product number.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>productnumber</td></tr></table>

### <a href=#quantitySellingCode name="quantitySellingCode">quantitySellingCode</a>

Quantity of the product that must be sold for a given price level.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity Selling Option</td></tr><tr><td>description</td><td>Quantity of the product that must be sold for a given price level.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>quantitysellingcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>No Control</td><td>1</td></tr><tr><td>en</td><td>Whole</td><td>2</td></tr><tr><td>en</td><td>Whole and Fractional</td><td>3</td></tr></table></td></tr></table>

### <a href=#quantitySellingCode_display name="quantitySellingCode_display">quantitySellingCode_display</a>

First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#roundingOptionAmount name="roundingOptionAmount">roundingOptionAmount</a>

Rounding option amount for the price list.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rounding Amount</td></tr><tr><td>description</td><td>Rounding option amount for the price list.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>-100000000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>roundingoptionamount</td></tr></table>

### <a href=#roundingOptionAmountBase name="roundingOptionAmountBase">roundingOptionAmountBase</a>

Value of the Rounding Amount in base currency.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rounding Amount (Base)</td></tr><tr><td>description</td><td>Value of the Rounding Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>roundingoptionamount_base</td></tr></table>

### <a href=#roundingOptionCode name="roundingOptionCode">roundingOptionCode</a>

Option for rounding the price list.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rounding Option</td></tr><tr><td>description</td><td>Option for rounding the price list.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>roundingoptioncode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Ends in</td><td>1</td></tr><tr><td>en</td><td>Multiple of</td><td>2</td></tr></table></td></tr></table>

### <a href=#roundingOptionCode_display name="roundingOptionCode_display">roundingOptionCode_display</a>

First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#roundingPolicyCode name="roundingPolicyCode">roundingPolicyCode</a>

Policy for rounding the price list.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rounding Policy</td></tr><tr><td>description</td><td>Policy for rounding the price list.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>roundingpolicycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>1</td></tr><tr><td>en</td><td>Up</td><td>2</td></tr><tr><td>en</td><td>Down</td><td>3</td></tr><tr><td>en</td><td>To Nearest</td><td>4</td></tr></table></td></tr></table>

### <a href=#roundingPolicyCode_display name="roundingPolicyCode_display">roundingPolicyCode_display</a>

First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#uoMId name="uoMId">uoMId</a>

Unique identifier of the unit for the price list.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit</td></tr><tr><td>description</td><td>Unique identifier of the unit for the price list.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>uomid</td></tr></table>

### <a href=#uoMScheduleId name="uoMScheduleId">uoMScheduleId</a>

Unique identifier of the unit schedule for the price list.  
First included in: <a href="../../PriceListItem.md" target="_blank">foundationCommon/PriceListItem</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit Schedule ID</td></tr><tr><td>description</td><td>Unique identifier of the unit schedule for the price list.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>uomscheduleid</td></tr></table>

### <a href=#discountTypeId name="discountTypeId">discountTypeId</a>

Unique identifier of the discount list associated with the price list.  
First included in: sales/PriceListItem (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount List</td></tr><tr><td>description</td><td>Unique identifier of the discount list associated with the price list.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>discounttypeid</td></tr></table>
