---
title: Product - Common Data Model | Microsoft Docs
description: Information about products and their prices.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Product

Information about products and their prices.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Product.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- [/foundationCommon/Product](../../../../Product.md "/core/applicationCommon/foundationCommon/Product.cdm.json/Product")  
- [/foundationCommon/crmCommon/accelerators/financialServices/banking/Product](../../financialServices/banking/Product.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/financialServices/banking/Product.cdm.json/Product")  
- /foundationCommon/crmCommon/accelerators/healthCare/electronicMedicalRecords/Product  
- [/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/Product](../../../projectCommon/projectServiceAutomation/Product.md "/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/Product.cdm.json/Product")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[productId](#productId)|Unique identifier of the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[name](#name)|Name of the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[vendorID](#vendorID)|Unique identifier of vendor supplying the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[validFromDate](#validFromDate)|Date from which this product is valid.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[validToDate](#validToDate)|Date to which this product is valid.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[currentCost](#currentCost)|Current cost for the product item. Used in price calculations.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the product with respect to the base currency.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[currentCostBase](#currentCostBase)|Value of the Current Cost in base currency.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[defaultUoMId](#defaultUoMId)|Default unit for the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[defaultUoMScheduleId](#defaultUoMScheduleId)|Default unit group for the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[description](#description)|Description of the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[isKit](#isKit)|Information that specifies whether the product is a kit.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[isStockItem](#isStockItem)|Information about whether the product is a stock item.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[parentProductId](#parentProductId)|Specifies the parent product family hierarchy.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[price](#price)|List price of the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[priceBase](#priceBase)|Value of the List Price in base currency.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[productStructure](#productStructure)|Product Structure.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[productStructure_display](#productStructure_display)||<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[productNumber](#productNumber)|User-defined product ID.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[productTypeCode](#productTypeCode)|Type of product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[productTypeCode_display](#productTypeCode_display)||<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[productUrl](#productUrl)|URL for the Website associated with the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[quantityDecimal](#quantityDecimal)|Number of decimal places that can be used in monetary amounts for the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[quantityOnHand](#quantityOnHand)|Quantity of the product in stock.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[size](#size)|Product size.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[standardCost](#standardCost)|Standard cost of the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[standardCostBase](#standardCostBase)|Value of the Standard Cost in base currency.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[stateCode](#stateCode)|Status of the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[stateCode_display](#stateCode_display)||<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[statusCode](#statusCode)|Reason for the status of the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[statusCode_display](#statusCode_display)||<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[stockVolume](#stockVolume)|Stock volume of the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[stockWeight](#stockWeight)|Stock weight of the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[supplierName](#supplierName)|Name of the product's supplier.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[vendorName](#vendorName)|Name of the product vendor.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[vendorPartNumber](#vendorPartNumber)|Unique part identifier in vendor catalog of this product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[hierarchyPath](#hierarchyPath)|Hierarchy path of the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[priceLevelId](#priceLevelId)|Select the default price list for the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[subjectId](#subjectId)|Select a category for the product.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[entityImageId](#entityImageId)||<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[createdByExternalParty](#createdByExternalParty)|Shows the external party who created the record.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[modifiedByExternalParty](#modifiedByExternalParty)|Shows the external party who modified the record.|<a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>|
|[form](#form)|Describes the form of the item. Powder; tablets; capsule.|<a href="Product.md" target="_blank">electronicMedicalRecords/Product</a>|
|[isBrand](#isBrand)|Set to true if the item is attributable to a specific manufacturer.|<a href="Product.md" target="_blank">electronicMedicalRecords/Product</a>|
|[isOvertheCounter](#isOvertheCounter)|Set to true if the medication can be obtained without an order from a prescriber.|<a href="Product.md" target="_blank">electronicMedicalRecords/Product</a>|
|[medicationCode](#medicationCode)|A code (or set of codes) that specify this medication, or a textual description if no code is available. Usage note: This could be a standard medication code.|<a href="Product.md" target="_blank">electronicMedicalRecords/Product</a>|
|[packageContainer](#packageContainer)|The kind of container that this package comes as.|<a href="Product.md" target="_blank">electronicMedicalRecords/Product</a>|

### <a href=#productId name="productId">productId</a>

Unique identifier of the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product</td></tr><tr><td>description</td><td>Unique identifier of the product.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>productid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the product.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the product.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the product.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the product.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Name of the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Name of the product.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#vendorID name="vendorID">vendorID</a>

Unique identifier of vendor supplying the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor ID</td></tr><tr><td>description</td><td>Unique identifier of vendor supplying the product.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>vendorid</td></tr></table>

### <a href=#validFromDate name="validFromDate">validFromDate</a>

Date from which this product is valid.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Valid From</td></tr><tr><td>description</td><td>Date from which this product is valid.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>validfromdate</td></tr></table>

### <a href=#validToDate name="validToDate">validToDate</a>

Date to which this product is valid.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Valid To</td></tr><tr><td>description</td><td>Date to which this product is valid.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>validtodate</td></tr></table>

### <a href=#currentCost name="currentCost">currentCost</a>

Current cost for the product item. Used in price calculations.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current Cost</td></tr><tr><td>description</td><td>Current cost for the product item. Used in price calculations.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>currentcost</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the product.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the product with respect to the base currency.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the product with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#currentCostBase name="currentCostBase">currentCostBase</a>

Value of the Current Cost in base currency.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current Cost (Base)</td></tr><tr><td>description</td><td>Value of the Current Cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>currentcost_base</td></tr></table>

### <a href=#defaultUoMId name="defaultUoMId">defaultUoMId</a>

Default unit for the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Unit</td></tr><tr><td>description</td><td>Default unit for the product.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>defaultuomid</td></tr></table>

### <a href=#defaultUoMScheduleId name="defaultUoMScheduleId">defaultUoMScheduleId</a>

Default unit group for the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit Group</td></tr><tr><td>description</td><td>Default unit group for the product.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>defaultuomscheduleid</td></tr></table>

### <a href=#description name="description">description</a>

Description of the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Description of the product.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#isKit name="isKit">isKit</a>

Information that specifies whether the product is a kit.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Kit</td></tr><tr><td>description</td><td>Information that specifies whether the product is a kit.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>iskit</td></tr></table>

### <a href=#isStockItem name="isStockItem">isStockItem</a>

Information about whether the product is a stock item.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stock Item</td></tr><tr><td>description</td><td>Information about whether the product is a stock item.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isstockitem</td></tr></table>

### <a href=#parentProductId name="parentProductId">parentProductId</a>

Specifies the parent product family hierarchy.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent</td></tr><tr><td>description</td><td>Specifies the parent product family hierarchy.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentproductid</td></tr></table>

### <a href=#price name="price">price</a>

List price of the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>List Price</td></tr><tr><td>description</td><td>List price of the product.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>price</td></tr></table>

### <a href=#priceBase name="priceBase">priceBase</a>

Value of the List Price in base currency.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>List Price (Base)</td></tr><tr><td>description</td><td>Value of the List Price in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>price_base</td></tr></table>

### <a href=#productStructure name="productStructure">productStructure</a>

Product Structure.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product Structure</td></tr><tr><td>description</td><td>Product Structure.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>productstructure</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Product</td><td>1</td></tr><tr><td>en</td><td>Product Family</td><td>2</td></tr><tr><td>en</td><td>Product Bundle</td><td>3</td></tr></table></td></tr></table>

### <a href=#productStructure_display name="productStructure_display">productStructure_display</a>

First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#productNumber name="productNumber">productNumber</a>

User-defined product ID.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product ID</td></tr><tr><td>description</td><td>User-defined product ID.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>productnumber</td></tr></table>

### <a href=#productTypeCode name="productTypeCode">productTypeCode</a>

Type of product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product Type</td></tr><tr><td>description</td><td>Type of product.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>producttypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Sales Inventory</td><td>1</td></tr><tr><td>en</td><td>Miscellaneous Charges</td><td>2</td></tr><tr><td>en</td><td>Services</td><td>3</td></tr><tr><td>en</td><td>Flat Fees</td><td>4</td></tr></table></td></tr></table>

### <a href=#productTypeCode_display name="productTypeCode_display">productTypeCode_display</a>

First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#productUrl name="productUrl">productUrl</a>

URL for the Website associated with the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>URL</td></tr><tr><td>description</td><td>URL for the Website associated with the product.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>producturl</td></tr></table>

### <a href=#quantityDecimal name="quantityDecimal">quantityDecimal</a>

Number of decimal places that can be used in monetary amounts for the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Decimals Supported</td></tr><tr><td>description</td><td>Number of decimal places that can be used in monetary amounts for the product.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>5</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>quantitydecimal</td></tr></table>

### <a href=#quantityOnHand name="quantityOnHand">quantityOnHand</a>

Quantity of the product in stock.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity On Hand</td></tr><tr><td>description</td><td>Quantity of the product in stock.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>quantityonhand</td></tr></table>

### <a href=#size name="size">size</a>

Product size.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Size</td></tr><tr><td>description</td><td>Product size.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>size</td></tr></table>

### <a href=#standardCost name="standardCost">standardCost</a>

Standard cost of the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Standard Cost</td></tr><tr><td>description</td><td>Standard cost of the product.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>standardcost</td></tr></table>

### <a href=#standardCostBase name="standardCostBase">standardCostBase</a>

Value of the Standard Cost in base currency.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Standard Cost (Base)</td></tr><tr><td>description</td><td>Value of the Standard Cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>standardcost_base</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the product.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Retired</td><td>1</td></tr><tr><td>en</td><td>Draft</td><td>2</td></tr><tr><td>en</td><td>Under Revision</td><td>3</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the product.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Retired</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Draft</td><td>0</td><td>2</td></tr><tr><td>en</td><td>Under Revision</td><td>3</td><td>3</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#stockVolume name="stockVolume">stockVolume</a>

Stock volume of the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stock Volume</td></tr><tr><td>description</td><td>Stock volume of the product.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stockvolume</td></tr></table>

### <a href=#stockWeight name="stockWeight">stockWeight</a>

Stock weight of the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stock Weight</td></tr><tr><td>description</td><td>Stock weight of the product.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stockweight</td></tr></table>

### <a href=#supplierName name="supplierName">supplierName</a>

Name of the product's supplier.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Supplier Name</td></tr><tr><td>description</td><td>Name of the product's supplier.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>suppliername</td></tr></table>

### <a href=#vendorName name="vendorName">vendorName</a>

Name of the product vendor.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor</td></tr><tr><td>description</td><td>Name of the product vendor.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>vendorname</td></tr></table>

### <a href=#vendorPartNumber name="vendorPartNumber">vendorPartNumber</a>

Unique part identifier in vendor catalog of this product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor Name</td></tr><tr><td>description</td><td>Unique part identifier in vendor catalog of this product.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>vendorpartnumber</td></tr></table>

### <a href=#hierarchyPath name="hierarchyPath">hierarchyPath</a>

Hierarchy path of the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hierarchy Path</td></tr><tr><td>description</td><td>Hierarchy path of the product.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>450</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>hierarchypath</td></tr></table>

### <a href=#priceLevelId name="priceLevelId">priceLevelId</a>

Select the default price list for the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Price List</td></tr><tr><td>description</td><td>Select the default price list for the product.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>pricelevelid</td></tr></table>

### <a href=#subjectId name="subjectId">subjectId</a>

Select a category for the product.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subject</td></tr><tr><td>description</td><td>Select a category for the product.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>subjectid</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

### <a href=#createdByExternalParty name="createdByExternalParty">createdByExternalParty</a>

Shows the external party who created the record.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (External Party)</td></tr><tr><td>description</td><td>Shows the external party who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdbyexternalparty</td></tr></table>

### <a href=#modifiedByExternalParty name="modifiedByExternalParty">modifiedByExternalParty</a>

Shows the external party who modified the record.  
First included in: <a href="../../../../Product.md" target="_blank">foundationCommon/Product</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (External Party)</td></tr><tr><td>description</td><td>Shows the external party who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedbyexternalparty</td></tr></table>

### <a href=#form name="form">form</a>

Describes the form of the item. Powder; tablets; capsule.  
First included in: electronicMedicalRecords/Product (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Form</td></tr><tr><td>description</td><td>Describes the form of the item. Powder; tablets; capsule.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_form</td></tr></table>

### <a href=#isBrand name="isBrand">isBrand</a>

Set to true if the item is attributable to a specific manufacturer.  
First included in: electronicMedicalRecords/Product (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Brand</td></tr><tr><td>description</td><td>Set to true if the item is attributable to a specific manufacturer.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_isbrand</td></tr></table>

### <a href=#isOvertheCounter name="isOvertheCounter">isOvertheCounter</a>

Set to true if the medication can be obtained without an order from a prescriber.  
First included in: electronicMedicalRecords/Product (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Over the Counter</td></tr><tr><td>description</td><td>Set to true if the medication can be obtained without an order from a prescriber.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_isoverthecounter</td></tr></table>

### <a href=#medicationCode name="medicationCode">medicationCode</a>

A code (or set of codes) that specify this medication, or a textual description if no code is available. Usage note: This could be a standard medication code.  
First included in: electronicMedicalRecords/Product (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Medication Code</td></tr><tr><td>description</td><td>A code (or set of codes) that specify this medication, or a textual description if no code is available. Usage note: This could be a standard medication code.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_medicationcode</td></tr></table>

### <a href=#packageContainer name="packageContainer">packageContainer</a>

The kind of container that this package comes as.  
First included in: electronicMedicalRecords/Product (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Package Container</td></tr><tr><td>description</td><td>The kind of container that this package comes as.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msemr_packagecontainer</td></tr></table>
