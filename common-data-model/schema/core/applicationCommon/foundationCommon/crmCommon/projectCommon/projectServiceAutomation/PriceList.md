---
title: PriceList - Common Data Model | Microsoft Docs
description: Entity that defines pricing levels.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Price List

Entity that defines pricing levels.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/PriceList.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/foundationCommon/PriceList](../../../PriceList.md "/core/applicationCommon/foundationCommon/PriceList.cdm.json/PriceList")  
- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/PriceList  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[priceLevelId](#priceLevelId)|Unique identifier of the price list.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the price list.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the price list.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the pricelevel.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the pricelevel.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[name](#name)|Name of the price list.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[beginDate](#beginDate)|Date on which the price list becomes effective.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[description](#description)|Description of the price list.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[endDate](#endDate)|Date that is the last day the price list is valid.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[freightTermsCode](#freightTermsCode)|Freight terms for the price list.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[freightTermsCode_display](#freightTermsCode_display)||<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[paymentMethodCode](#paymentMethodCode)|Payment terms to use with the price list.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[paymentMethodCode_display](#paymentMethodCode_display)||<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[shippingMethodCode](#shippingMethodCode)|Method of shipment for products in the price list.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[shippingMethodCode_display](#shippingMethodCode_display)||<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[stateCode](#stateCode)|Status of the price list.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[stateCode_display](#stateCode_display)||<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[statusCode](#statusCode)|Reason for the status of the price list.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[statusCode_display](#statusCode_display)||<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the price level.|<a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>|
|[copiedFromPriceLevel](#copiedFromPriceLevel)|Shows the price level that this price level was copied from.|<a href="PriceList.md" target="_blank">projectServiceAutomation/PriceList</a>|
|[entity](#entity)|Select the entity for this price level.|<a href="PriceList.md" target="_blank">projectServiceAutomation/PriceList</a>|
|[entity_display](#entity_display)||<a href="PriceList.md" target="_blank">projectServiceAutomation/PriceList</a>|
|[module](#module)|Select the context for this price level i.e whether it is sales prices, cost prices or purchase prices|<a href="PriceList.md" target="_blank">projectServiceAutomation/PriceList</a>|
|[module_display](#module_display)||<a href="PriceList.md" target="_blank">projectServiceAutomation/PriceList</a>|
|[timeUnit](#timeUnit)|Select the default unit of role based time on this price list|<a href="PriceList.md" target="_blank">projectServiceAutomation/PriceList</a>|

### <a href=#priceLevelId name="priceLevelId">priceLevelId</a>

Unique identifier of the price list.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price List</td></tr><tr><td>description</td><td>Unique identifier of the price list.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>pricelevelid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the price list.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the price list.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the price list.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the price list.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the pricelevel.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the pricelevel.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the pricelevel.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the pricelevel.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Name of the price list.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the price list.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#beginDate name="beginDate">beginDate</a>

Date on which the price list becomes effective.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start Date</td></tr><tr><td>description</td><td>Date on which the price list becomes effective.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>begindate</td></tr></table>

### <a href=#description name="description">description</a>

Description of the price list.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the price list.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#endDate name="endDate">endDate</a>

Date that is the last day the price list is valid.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>End Date</td></tr><tr><td>description</td><td>Date that is the last day the price list is valid.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>enddate</td></tr></table>

### <a href=#freightTermsCode name="freightTermsCode">freightTermsCode</a>

Freight terms for the price list.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freight Terms</td></tr><tr><td>description</td><td>Freight terms for the price list.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>freighttermscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#freightTermsCode_display name="freightTermsCode_display">freightTermsCode_display</a>

First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#paymentMethodCode name="paymentMethodCode">paymentMethodCode</a>

Payment terms to use with the price list.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment Method </td></tr><tr><td>description</td><td>Payment terms to use with the price list.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>paymentmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#paymentMethodCode_display name="paymentMethodCode_display">paymentMethodCode_display</a>

First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#shippingMethodCode name="shippingMethodCode">shippingMethodCode</a>

Method of shipment for products in the price list.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping Method</td></tr><tr><td>description</td><td>Method of shipment for products in the price list.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#shippingMethodCode_display name="shippingMethodCode_display">shippingMethodCode_display</a>

First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the price list.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status </td></tr><tr><td>description</td><td>Status of the price list.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the price list.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the price list.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>100001</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>100002</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the price level.  
First included in: <a href="../../../PriceList.md" target="_blank">foundationCommon/PriceList</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the price level.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#copiedFromPriceLevel name="copiedFromPriceLevel">copiedFromPriceLevel</a>

Shows the price level that this price level was copied from.  
First included in: projectServiceAutomation/PriceList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Copied From</td></tr><tr><td>description</td><td>Shows the price level that this price level was copied from.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_copiedfrompricelevel</td></tr></table>

### <a href=#entity name="entity">entity</a>

Select the entity for this price level.  
First included in: projectServiceAutomation/PriceList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entity</td></tr><tr><td>description</td><td>Select the entity for this price level.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_entity</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Organization</td><td>192350000</td></tr><tr><td>en</td><td>Customer</td><td>192350001</td></tr><tr><td>en</td><td>Sales document</td><td>192350002</td></tr><tr><td>en</td><td>Project</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#entity_display name="entity_display">entity_display</a>

First included in: projectServiceAutomation/PriceList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#module name="module">module</a>

Select the context for this price level i.e whether it is sales prices, cost prices or purchase prices  
First included in: projectServiceAutomation/PriceList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Context</td></tr><tr><td>description</td><td>Select the context for this price level i.e whether it is sales prices, cost prices or purchase prices</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_module</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Cost</td><td>192350000</td></tr><tr><td>en</td><td>Purchase</td><td>192350001</td></tr><tr><td>en</td><td>Sales</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#module_display name="module_display">module_display</a>

First included in: projectServiceAutomation/PriceList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#timeUnit name="timeUnit">timeUnit</a>

Select the default unit of role based time on this price list  
First included in: projectServiceAutomation/PriceList (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Unit</td></tr><tr><td>description</td><td>Select the default unit of role based time on this price list</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_timeunit</td></tr></table>
