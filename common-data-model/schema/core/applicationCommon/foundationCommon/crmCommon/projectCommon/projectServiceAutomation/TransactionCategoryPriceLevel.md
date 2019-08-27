---
title: TransactionCategoryPriceLevel - Common Data Model | Microsoft Docs
description: List of prices by category on a price list.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Transaction Category Price

List of prices by category on a price list.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/TransactionCategoryPriceLevel.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/TransactionCategoryPriceLevel  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[transactionCategoryPriceLevelId](#transactionCategoryPriceLevelId)|Unique identifier for entity instances|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[stateCode](#stateCode)|Status of the Transaction Category Price|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[stateCode_display](#stateCode_display)||<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[statusCode](#statusCode)|Reason for the status of the Transaction Category Price|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[statusCode_display](#statusCode_display)||<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[description](#description)|Type the name of the custom entity.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[percent](#percent)|Enter the mark up on cost when creating billable transactions from cost transactions. This field is relevant only when the price calculation is "Markup over cost." |<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[price](#price)|Enter the price of the transaction category.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Shows the currency associated with the entity.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[priceBase](#priceBase)|Value of the Price in base currency.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[priceCalculation](#priceCalculation)|Select the method used to determine the sales or bill rate of expenses in this category. Valid values are Price per unit, At cost or Markup over cost.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[priceCalculation_display](#priceCalculation_display)||<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[priceList](#priceList)|Select the price list that this price list line belongs to.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[transactionCategory](#transactionCategory)|Select the transaction category whose price is being setup|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[unit](#unit)|Select the units that transactions of this category can be expressed in.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|
|[unitSchedule](#unitSchedule)|Select the unit schedule that determines in which units the category can be priced.|<a href="TransactionCategoryPriceLevel.md" target="_blank">projectServiceAutomation/TransactionCategoryPriceLevel</a>|

### <a href=#transactionCategoryPriceLevelId name="transactionCategoryPriceLevelId">transactionCategoryPriceLevelId</a>

Unique identifier for entity instances  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Category Price</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msdyn_transactioncategorypricelevelid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Transaction Category Price  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Transaction Category Price</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Transaction Category Price  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Transaction Category Price</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#description name="description">description</a>

Type the name of the custom entity.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type the name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_description</td></tr></table>

### <a href=#percent name="percent">percent</a>

Enter the mark up on cost when creating billable transactions from cost transactions. This field is relevant only when the price calculation is "Markup over cost."   
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percent</td></tr><tr><td>description</td><td>Enter the mark up on cost when creating billable transactions from cost transactions. This field is relevant only when the price calculation is "Markup over cost." </td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_percent</td></tr></table>

### <a href=#price name="price">price</a>

Enter the price of the transaction category.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price</td></tr><tr><td>description</td><td>Enter the price of the transaction category.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_price</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Shows the currency associated with the entity.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Shows the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#priceBase name="priceBase">priceBase</a>

Value of the Price in base currency.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price (Base)</td></tr><tr><td>description</td><td>Value of the Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_price_base</td></tr></table>

### <a href=#priceCalculation name="priceCalculation">priceCalculation</a>

Select the method used to determine the sales or bill rate of expenses in this category. Valid values are Price per unit, At cost or Markup over cost.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price Calculation</td></tr><tr><td>description</td><td>Select the method used to determine the sales or bill rate of expenses in this category. Valid values are Price per unit, At cost or Markup over cost.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_pricecalculation</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Price per unit</td><td>192350000</td></tr><tr><td>en</td><td>At cost</td><td>192350001</td></tr><tr><td>en</td><td>Markup percentage</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#priceCalculation_display name="priceCalculation_display">priceCalculation_display</a>

First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#priceList name="priceList">priceList</a>

Select the price list that this price list line belongs to.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price List</td></tr><tr><td>description</td><td>Select the price list that this price list line belongs to.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_pricelist</td></tr></table>

### <a href=#transactionCategory name="transactionCategory">transactionCategory</a>

Select the transaction category whose price is being setup  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Category</td></tr><tr><td>description</td><td>Select the transaction category whose price is being setup</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_transactioncategory</td></tr></table>

### <a href=#unit name="unit">unit</a>

Select the units that transactions of this category can be expressed in.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit</td></tr><tr><td>description</td><td>Select the units that transactions of this category can be expressed in.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_unit</td></tr></table>

### <a href=#unitSchedule name="unitSchedule">unitSchedule</a>

Select the unit schedule that determines in which units the category can be priced.  
First included in: projectServiceAutomation/TransactionCategoryPriceLevel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit Schedule</td></tr><tr><td>description</td><td>Select the unit schedule that determines in which units the category can be priced.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_unitschedule</td></tr></table>
