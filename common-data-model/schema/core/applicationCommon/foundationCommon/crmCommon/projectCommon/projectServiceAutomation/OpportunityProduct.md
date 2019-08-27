---
title: OpportunityProduct - Common Data Model | Microsoft Docs
description: Association between an opportunity and a product.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Opportunity Product

Association between an opportunity and a product.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/OpportunityProduct.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/OpportunityProduct  
- [/foundationCommon/crmCommon/sales/OpportunityProduct](../../sales/OpportunityProduct.md "/core/applicationCommon/foundationCommon/crmCommon/sales/OpportunityProduct.cdm.json/OpportunityProduct")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[opportunityProductId](#opportunityProductId)|Unique identifier of the opportunity product.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[baseAmount](#baseAmount)|Shows the total price of the opportunity product, based on the price per unit, volume discount, and quantity.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[baseAmountBase](#baseAmountBase)|Value of the Amount in base currency.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[description](#description)|Type additional information to describe the opportunity product, such as manufacturing details.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[extendedAmount](#extendedAmount)|Shows the total amount due for the opportunity product, calculated on the Amount value minus the Manual Discount amount.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[extendedAmountBase](#extendedAmountBase)|Value of the Extended Amount in base currency.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[isPriceOverridden](#isPriceOverridden)|Select whether the pricing on the opportunity product reflects an override of the product catalog pricing.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[isProductOverridden](#isProductOverridden)|For system use only.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[lineItemNumber](#lineItemNumber)|Type the line item number for the opportunity product to easily identify the product in the opportunity documents and make sure it's listed in the correct order.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[manualDiscountAmount](#manualDiscountAmount)|Type the manual discount amount for the opportunity product to deduct any negotiated or other savings from the product total.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[manualDiscountAmountBase](#manualDiscountAmountBase)|Value of the Manual Discount Amount in base currency.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[opportunityId](#opportunityId)|Unique identifier of the opportunity with which the opportunity product is associated.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[opportunityStateCode](#opportunityStateCode)|Select the status of the opportunity product.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[opportunityStateCode_display](#opportunityStateCode_display)||<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[parentBundleId](#parentBundleId)|Choose the parent bundle associated with this product|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[productAssociationId](#productAssociationId)|Unique identifier of the product line item association with bundle in the opportunity|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[productTypeCode](#productTypeCode)|Product Type|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[productTypeCode_display](#productTypeCode_display)||<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[pricePerUnit](#pricePerUnit)|Shows the price per unit of the opportunity product, based on the price list specified on the parent opportunity.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[pricePerUnitBase](#pricePerUnitBase)|Value of the Price Per Unit in base currency.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[pricingErrorCode](#pricingErrorCode)|Select the pricing error for the opportunity product.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[pricingErrorCode_display](#pricingErrorCode_display)||<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[productDescription](#productDescription)|Type a detailed product description or additional notes about the opportunity product, such as talking points or product updates, that will assist the sales team when they discuss the product with the customer.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[productName](#productName)|Calculated field that will be populated by name and description of the product.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[productId](#productId)|Choose the product to include on the opportunity to link the product's pricing and other information to the opportunity.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[quantity](#quantity)|Type the amount or quantity of the product the customer would like to purchase.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[tax](#tax)|Type the tax amount to be applied on the opportunity product.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[taxBase](#taxBase)|Value of the Tax in base currency.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[uoMId](#uoMId)|Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[volumeDiscountAmount](#volumeDiscountAmount)|Shows the discount amount per unit if a specified volume is purchased. Configure volume discounts in the Product Catalog in the Settings area.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[volumeDiscountAmountBase](#volumeDiscountAmountBase)|Value of the Volume Discount in base currency.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[sequenceNumber](#sequenceNumber)|Shows the ID of the data that maintains the sequence.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[propertyConfigurationStatus](#propertyConfigurationStatus)|Status of the property configuration.|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[propertyConfigurationStatus_display](#propertyConfigurationStatus_display)||<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[entityImageId](#entityImageId)||<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[opportunityProductName](#opportunityProductName)|Opportunity Product Name. Added for 1:n Referential relationship|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[parentBundleIdRef](#parentBundleIdRef)|Choose the parent bundle associated with this product|<a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>|
|[billingMethod](#billingMethod)|Billing method for the project opportunity line. Valid values are Time and Material and Fixed Price|<a href="OpportunityProduct.md" target="_blank">projectServiceAutomation/OpportunityProduct</a>|
|[billingMethod_display](#billingMethod_display)||<a href="OpportunityProduct.md" target="_blank">projectServiceAutomation/OpportunityProduct</a>|
|[budgetAmount](#budgetAmount)|Enter the customer budget amount for this opportunity line.|<a href="OpportunityProduct.md" target="_blank">projectServiceAutomation/OpportunityProduct</a>|
|[budgetAmountBase](#budgetAmountBase)|Value of the Budget Amount in base currency.|<a href="OpportunityProduct.md" target="_blank">projectServiceAutomation/OpportunityProduct</a>|
|[costAmount](#costAmount)|Shows the total cost price of the product based on the cost price per unit and quantity.|<a href="OpportunityProduct.md" target="_blank">projectServiceAutomation/OpportunityProduct</a>|
|[costAmountBase](#costAmountBase)|Value of the Cost Amount in base currency.|<a href="OpportunityProduct.md" target="_blank">projectServiceAutomation/OpportunityProduct</a>|
|[costPricePerUnit](#costPricePerUnit)|Cost price per unit of the product. The default is the cost price of the product.|<a href="OpportunityProduct.md" target="_blank">projectServiceAutomation/OpportunityProduct</a>|
|[costPricePerUnitBase](#costPricePerUnitBase)|Value of the Cost Price Per Unit in base currency.|<a href="OpportunityProduct.md" target="_blank">projectServiceAutomation/OpportunityProduct</a>|
|[lineType](#lineType)|The field to distinguish the order lines to be of project service or field service|<a href="OpportunityProduct.md" target="_blank">projectServiceAutomation/OpportunityProduct</a>|
|[lineType_display](#lineType_display)||<a href="OpportunityProduct.md" target="_blank">projectServiceAutomation/OpportunityProduct</a>|
|[project](#project)|Select the project for this opportunity line.|<a href="OpportunityProduct.md" target="_blank">projectServiceAutomation/OpportunityProduct</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#opportunityProductId name="opportunityProductId">opportunityProductId</a>

Unique identifier of the opportunity product.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Opportunity Product</td></tr><tr><td>description</td><td>Unique identifier of the opportunity product.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>opportunityproductid</td></tr></table>

### <a href=#baseAmount name="baseAmount">baseAmount</a>

Shows the total price of the opportunity product, based on the price per unit, volume discount, and quantity.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount</td></tr><tr><td>description</td><td>Shows the total price of the opportunity product, based on the price per unit, volume discount, and quantity.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>baseamount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#baseAmountBase name="baseAmountBase">baseAmountBase</a>

Value of the Amount in base currency.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base)</td></tr><tr><td>description</td><td>Value of the Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>baseamount_base</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the opportunity product, such as manufacturing details.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the opportunity product, such as manufacturing details.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#extendedAmount name="extendedAmount">extendedAmount</a>

Shows the total amount due for the opportunity product, calculated on the Amount value minus the Manual Discount amount.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Extended Amount</td></tr><tr><td>description</td><td>Shows the total amount due for the opportunity product, calculated on the Amount value minus the Manual Discount amount.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>extendedamount</td></tr></table>

### <a href=#extendedAmountBase name="extendedAmountBase">extendedAmountBase</a>

Value of the Extended Amount in base currency.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Extended Amount (Base)</td></tr><tr><td>description</td><td>Value of the Extended Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>extendedamount_base</td></tr></table>

### <a href=#isPriceOverridden name="isPriceOverridden">isPriceOverridden</a>

Select whether the pricing on the opportunity product reflects an override of the product catalog pricing.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price Overridden</td></tr><tr><td>description</td><td>Select whether the pricing on the opportunity product reflects an override of the product catalog pricing.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ispriceoverridden</td></tr></table>

### <a href=#isProductOverridden name="isProductOverridden">isProductOverridden</a>

For system use only.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Select Product</td></tr><tr><td>description</td><td>For system use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isproductoverridden</td></tr></table>

### <a href=#lineItemNumber name="lineItemNumber">lineItemNumber</a>

Type the line item number for the opportunity product to easily identify the product in the opportunity documents and make sure it's listed in the correct order.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line Item Number</td></tr><tr><td>description</td><td>Type the line item number for the opportunity product to easily identify the product in the opportunity documents and make sure it's listed in the correct order.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lineitemnumber</td></tr></table>

### <a href=#manualDiscountAmount name="manualDiscountAmount">manualDiscountAmount</a>

Type the manual discount amount for the opportunity product to deduct any negotiated or other savings from the product total.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manual Discount Amount</td></tr><tr><td>description</td><td>Type the manual discount amount for the opportunity product to deduct any negotiated or other savings from the product total.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>manualdiscountamount</td></tr></table>

### <a href=#manualDiscountAmountBase name="manualDiscountAmountBase">manualDiscountAmountBase</a>

Value of the Manual Discount Amount in base currency.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manual Discount Amount (Base)</td></tr><tr><td>description</td><td>Value of the Manual Discount Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>manualdiscountamount_base</td></tr></table>

### <a href=#opportunityId name="opportunityId">opportunityId</a>

Unique identifier of the opportunity with which the opportunity product is associated.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Opportunity</td></tr><tr><td>description</td><td>Unique identifier of the opportunity with which the opportunity product is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>opportunityid</td></tr></table>

### <a href=#opportunityStateCode name="opportunityStateCode">opportunityStateCode</a>

Select the status of the opportunity product.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Opportunity Status</td></tr><tr><td>description</td><td>Select the status of the opportunity product.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>opportunitystatecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#opportunityStateCode_display name="opportunityStateCode_display">opportunityStateCode_display</a>

First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#parentBundleId name="parentBundleId">parentBundleId</a>

Choose the parent bundle associated with this product  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Bundle</td></tr><tr><td>description</td><td>Choose the parent bundle associated with this product</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentbundleid</td></tr></table>

### <a href=#productAssociationId name="productAssociationId">productAssociationId</a>

Unique identifier of the product line item association with bundle in the opportunity  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bundle Item Association</td></tr><tr><td>description</td><td>Unique identifier of the product line item association with bundle in the opportunity</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>productassociationid</td></tr></table>

### <a href=#productTypeCode name="productTypeCode">productTypeCode</a>

Product Type  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product type</td></tr><tr><td>description</td><td>Product Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>producttypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Product</td><td>1</td></tr><tr><td>en</td><td>Bundle</td><td>2</td></tr><tr><td>en</td><td>Required Bundle Product</td><td>3</td></tr><tr><td>en</td><td>Optional Bundle Product</td><td>4</td></tr><tr><td>en</td><td>Project-based Service</td><td>5</td></tr></table></td></tr></table>

### <a href=#productTypeCode_display name="productTypeCode_display">productTypeCode_display</a>

First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#pricePerUnit name="pricePerUnit">pricePerUnit</a>

Shows the price per unit of the opportunity product, based on the price list specified on the parent opportunity.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price Per Unit</td></tr><tr><td>description</td><td>Shows the price per unit of the opportunity product, based on the price list specified on the parent opportunity.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>priceperunit</td></tr></table>

### <a href=#pricePerUnitBase name="pricePerUnitBase">pricePerUnitBase</a>

Value of the Price Per Unit in base currency.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price Per Unit (Base)</td></tr><tr><td>description</td><td>Value of the Price Per Unit in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>priceperunit_base</td></tr></table>

### <a href=#pricingErrorCode name="pricingErrorCode">pricingErrorCode</a>

Select the pricing error for the opportunity product.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pricing Error </td></tr><tr><td>description</td><td>Select the pricing error for the opportunity product.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>pricingerrorcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>0</td></tr><tr><td>en</td><td>Detail Error</td><td>1</td></tr><tr><td>en</td><td>Missing Price Level</td><td>2</td></tr><tr><td>en</td><td>Inactive Price Level</td><td>3</td></tr><tr><td>en</td><td>Missing Quantity</td><td>4</td></tr><tr><td>en</td><td>Missing Unit Price</td><td>5</td></tr><tr><td>en</td><td>Missing Product</td><td>6</td></tr><tr><td>en</td><td>Invalid Product</td><td>7</td></tr><tr><td>en</td><td>Missing Pricing Code</td><td>8</td></tr><tr><td>en</td><td>Invalid Pricing Code</td><td>9</td></tr><tr><td>en</td><td>Missing UOM</td><td>10</td></tr><tr><td>en</td><td>Product Not In Price Level</td><td>11</td></tr><tr><td>en</td><td>Missing Price Level Amount</td><td>12</td></tr><tr><td>en</td><td>Missing Price Level Percentage</td><td>13</td></tr><tr><td>en</td><td>Missing Price</td><td>14</td></tr><tr><td>en</td><td>Missing Current Cost</td><td>15</td></tr><tr><td>en</td><td>Missing Standard Cost</td><td>16</td></tr><tr><td>en</td><td>Invalid Price Level Amount</td><td>17</td></tr><tr><td>en</td><td>Invalid Price Level Percentage</td><td>18</td></tr><tr><td>en</td><td>Invalid Price</td><td>19</td></tr><tr><td>en</td><td>Invalid Current Cost</td><td>20</td></tr><tr><td>en</td><td>Invalid Standard Cost</td><td>21</td></tr><tr><td>en</td><td>Invalid Rounding Policy</td><td>22</td></tr><tr><td>en</td><td>Invalid Rounding Option</td><td>23</td></tr><tr><td>en</td><td>Invalid Rounding Amount</td><td>24</td></tr><tr><td>en</td><td>Price Calculation Error</td><td>25</td></tr><tr><td>en</td><td>Invalid Discount Type</td><td>26</td></tr><tr><td>en</td><td>Discount Type Invalid State</td><td>27</td></tr><tr><td>en</td><td>Invalid Discount</td><td>28</td></tr><tr><td>en</td><td>Invalid Quantity</td><td>29</td></tr><tr><td>en</td><td>Invalid Pricing Precision</td><td>30</td></tr><tr><td>en</td><td>Missing Product Default UOM</td><td>31</td></tr><tr><td>en</td><td>Missing Product UOM Schedule </td><td>32</td></tr><tr><td>en</td><td>Inactive Discount Type</td><td>33</td></tr><tr><td>en</td><td>Invalid Price Level Currency</td><td>34</td></tr><tr><td>en</td><td>Price Attribute Out Of Range</td><td>35</td></tr><tr><td>en</td><td>Base Currency Attribute Overflow</td><td>36</td></tr><tr><td>en</td><td>Base Currency Attribute Underflow</td><td>37</td></tr></table></td></tr></table>

### <a href=#pricingErrorCode_display name="pricingErrorCode_display">pricingErrorCode_display</a>

First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#productDescription name="productDescription">productDescription</a>

Type a detailed product description or additional notes about the opportunity product, such as talking points or product updates, that will assist the sales team when they discuss the product with the customer.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Write-In Product</td></tr><tr><td>description</td><td>Type a detailed product description or additional notes about the opportunity product, such as talking points or product updates, that will assist the sales team when they discuss the product with the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>productdescription</td></tr></table>

### <a href=#productName name="productName">productName</a>

Calculated field that will be populated by name and description of the product.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product Name</td></tr><tr><td>description</td><td>Calculated field that will be populated by name and description of the product.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>productname</td></tr></table>

### <a href=#productId name="productId">productId</a>

Choose the product to include on the opportunity to link the product's pricing and other information to the opportunity.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Existing Product</td></tr><tr><td>description</td><td>Choose the product to include on the opportunity to link the product's pricing and other information to the opportunity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>productid</td></tr></table>

### <a href=#quantity name="quantity">quantity</a>

Type the amount or quantity of the product the customer would like to purchase.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity</td></tr><tr><td>description</td><td>Type the amount or quantity of the product the customer would like to purchase.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>quantity</td></tr></table>

### <a href=#tax name="tax">tax</a>

Type the tax amount to be applied on the opportunity product.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax</td></tr><tr><td>description</td><td>Type the tax amount to be applied on the opportunity product.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>-100000000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>tax</td></tr></table>

### <a href=#taxBase name="taxBase">taxBase</a>

Value of the Tax in base currency.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax (Base)</td></tr><tr><td>description</td><td>Value of the Tax in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>tax_base</td></tr></table>

### <a href=#uoMId name="uoMId">uoMId</a>

Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit</td></tr><tr><td>description</td><td>Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>uomid</td></tr></table>

### <a href=#volumeDiscountAmount name="volumeDiscountAmount">volumeDiscountAmount</a>

Shows the discount amount per unit if a specified volume is purchased. Configure volume discounts in the Product Catalog in the Settings area.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Volume Discount</td></tr><tr><td>description</td><td>Shows the discount amount per unit if a specified volume is purchased. Configure volume discounts in the Product Catalog in the Settings area.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>volumediscountamount</td></tr></table>

### <a href=#volumeDiscountAmountBase name="volumeDiscountAmountBase">volumeDiscountAmountBase</a>

Value of the Volume Discount in base currency.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Volume Discount (Base)</td></tr><tr><td>description</td><td>Value of the Volume Discount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>volumediscountamount_base</td></tr></table>

### <a href=#sequenceNumber name="sequenceNumber">sequenceNumber</a>

Shows the ID of the data that maintains the sequence.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sequence Number</td></tr><tr><td>description</td><td>Shows the ID of the data that maintains the sequence.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sequencenumber</td></tr></table>

### <a href=#propertyConfigurationStatus name="propertyConfigurationStatus">propertyConfigurationStatus</a>

Status of the property configuration.  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Property Configuration</td></tr><tr><td>description</td><td>Status of the property configuration.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>propertyconfigurationstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Edit</td><td>0</td></tr><tr><td>en</td><td>Rectify</td><td>1</td></tr><tr><td>en</td><td>Not Configured</td><td>2</td></tr></table></td></tr></table>

### <a href=#propertyConfigurationStatus_display name="propertyConfigurationStatus_display">propertyConfigurationStatus_display</a>

First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

### <a href=#opportunityProductName name="opportunityProductName">opportunityProductName</a>

Opportunity Product Name. Added for 1:n Referential relationship  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Opportunity Product Name. Added for 1:n Referential relationship</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>opportunityproductname</td></tr></table>

### <a href=#parentBundleIdRef name="parentBundleIdRef">parentBundleIdRef</a>

Choose the parent bundle associated with this product  
First included in: <a href="../../sales/OpportunityProduct.md" target="_blank">sales/OpportunityProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent bundle product</td></tr><tr><td>description</td><td>Choose the parent bundle associated with this product</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentbundleidref</td></tr></table>

### <a href=#billingMethod name="billingMethod">billingMethod</a>

Billing method for the project opportunity line. Valid values are Time and Material and Fixed Price  
First included in: projectServiceAutomation/OpportunityProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing Method</td></tr><tr><td>description</td><td>Billing method for the project opportunity line. Valid values are Time and Material and Fixed Price</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_billingmethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Time and Material</td><td>192350000</td></tr><tr><td>en</td><td>Fixed Price</td><td>192350001</td></tr></table></td></tr></table>

### <a href=#billingMethod_display name="billingMethod_display">billingMethod_display</a>

First included in: projectServiceAutomation/OpportunityProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#budgetAmount name="budgetAmount">budgetAmount</a>

Enter the customer budget amount for this opportunity line.  
First included in: projectServiceAutomation/OpportunityProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget Amount</td></tr><tr><td>description</td><td>Enter the customer budget amount for this opportunity line.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_budgetamount</td></tr></table>

### <a href=#budgetAmountBase name="budgetAmountBase">budgetAmountBase</a>

Value of the Budget Amount in base currency.  
First included in: projectServiceAutomation/OpportunityProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget Amount (Base)</td></tr><tr><td>description</td><td>Value of the Budget Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_budgetamount_base</td></tr></table>

### <a href=#costAmount name="costAmount">costAmount</a>

Shows the total cost price of the product based on the cost price per unit and quantity.  
First included in: projectServiceAutomation/OpportunityProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Amount</td></tr><tr><td>description</td><td>Shows the total cost price of the product based on the cost price per unit and quantity.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costamount</td></tr></table>

### <a href=#costAmountBase name="costAmountBase">costAmountBase</a>

Value of the Cost Amount in base currency.  
First included in: projectServiceAutomation/OpportunityProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Amount (Base)</td></tr><tr><td>description</td><td>Value of the Cost Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costamount_base</td></tr></table>

### <a href=#costPricePerUnit name="costPricePerUnit">costPricePerUnit</a>

Cost price per unit of the product. The default is the cost price of the product.  
First included in: projectServiceAutomation/OpportunityProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Price Per Unit</td></tr><tr><td>description</td><td>Cost price per unit of the product. The default is the cost price of the product.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costpriceperunit</td></tr></table>

### <a href=#costPricePerUnitBase name="costPricePerUnitBase">costPricePerUnitBase</a>

Value of the Cost Price Per Unit in base currency.  
First included in: projectServiceAutomation/OpportunityProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Price Per Unit (Base)</td></tr><tr><td>description</td><td>Value of the Cost Price Per Unit in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costpriceperunit_base</td></tr></table>

### <a href=#lineType name="lineType">lineType</a>

The field to distinguish the order lines to be of project service or field service  
First included in: projectServiceAutomation/OpportunityProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line Type</td></tr><tr><td>description</td><td>The field to distinguish the order lines to be of project service or field service</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_linetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Project Service Line</td><td>690970000</td></tr><tr><td>en</td><td>Field Service Line</td><td>690970001</td></tr></table></td></tr></table>

### <a href=#lineType_display name="lineType_display">lineType_display</a>

First included in: projectServiceAutomation/OpportunityProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#project name="project">project</a>

Select the project for this opportunity line.  
First included in: projectServiceAutomation/OpportunityProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project</td></tr><tr><td>description</td><td>Select the project for this opportunity line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_project</td></tr></table>
