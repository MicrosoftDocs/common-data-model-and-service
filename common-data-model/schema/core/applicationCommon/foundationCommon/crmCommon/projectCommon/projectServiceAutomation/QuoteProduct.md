---
title: QuoteProduct - Common Data Model | Microsoft Docs
description: This describes the QuoteProduct entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Quote Product

Product line item in a quote. The details include such information as product ID, description, quantity, and cost.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/QuoteProduct.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/QuoteProduct  
- [/foundationCommon/crmCommon/sales/QuoteProduct](../../sales/QuoteProduct.md "/core/applicationCommon/foundationCommon/crmCommon/sales/QuoteProduct.cdm.json/QuoteProduct")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[quoteDetailId](#quoteDetailId)|Unique identifier of the product line item in the quote.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[baseAmount](#baseAmount)|Shows the total price of the quote product, based on the price per unit, volume discount, and quantity.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[baseAmountBase](#baseAmountBase)|Value of the Amount in base currency.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[description](#description)|Type additional information to describe the quote product, such as manufacturing details or acceptable substitutions.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[extendedAmount](#extendedAmount)|Shows the total amount due for the quote product, based on the sum of the unit price, quantity, discounts ,and tax.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[extendedAmountBase](#extendedAmountBase)|Value of the Extended Amount in base currency.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[isPriceOverridden](#isPriceOverridden)|Select whether the price per unit is fixed at the value in the specified price list or can be overridden by users who have edit rights to the quote product.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[isProductOverridden](#isProductOverridden)|Select whether the product exists in the Microsoft Dynamics 365 product catalog or is a write-in product specific to the quote.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[lineItemNumber](#lineItemNumber)|Type the line item number for the quote product to easily identify the product in the quote and make sure it's listed in the correct order.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[manualDiscountAmount](#manualDiscountAmount)|Type the manual discount amount for the quote product to deduct any negotiated or other savings from the product total on the quote.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[manualDiscountAmountBase](#manualDiscountAmountBase)|Value of the Manual Discount in base currency.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[parentBundleId](#parentBundleId)|Choose the parent bundle associated with this product|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[productAssociationId](#productAssociationId)|Unique identifier of the product line item association with bundle in the quote|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[productTypeCode](#productTypeCode)|Product Type|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[productTypeCode_display](#productTypeCode_display)||<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[pricePerUnit](#pricePerUnit)|Type the price per unit of the quote product. The default is to the value in the price list specified on the quote for existing products.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[pricePerUnitBase](#pricePerUnitBase)|Value of the Price Per Unit in base currency.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[pricingErrorCode](#pricingErrorCode)|Select the type of pricing error, such as a missing or invalid product, or missing quantity.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[pricingErrorCode_display](#pricingErrorCode_display)||<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[productDescription](#productDescription)|Type a name or description to identify the type of write-in product included in the quote.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[productName](#productName)|Calculated field that will be populated by name and description of the product.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[productId](#productId)|Choose the product to include on the quote to link the product's pricing and other information to the quote.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[quantity](#quantity)|Type the amount or quantity of the product requested by the customer.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[quoteId](#quoteId)|Unique identifier of the quote for the quote product.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[quoteStateCode](#quoteStateCode)|Status of the quote product.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[quoteStateCode_display](#quoteStateCode_display)||<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[requestDeliveryBy](#requestDeliveryBy)|Enter the delivery date requested by the customer for the quote product.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[salesRepId](#salesRepId)|Choose the user responsible for the sale of the quote product.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[shipToAddressId](#shipToAddressId)|Unique identifier of the shipping address.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[shipToCity](#shipToCity)|Type the city for the customer's shipping address.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[shipToContactName](#shipToContactName)|Type the primary contact name at the customer's shipping address.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[shipToCountry](#shipToCountry)|Type the country or region for the customer's shipping address.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[shipToFax](#shipToFax)|Type the fax number for the customer's shipping address.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[shipToFreightTermsCode](#shipToFreightTermsCode)|Select the freight terms to make sure shipping orders are processed correctly.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[shipToFreightTermsCode_display](#shipToFreightTermsCode_display)||<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[shipToLine1](#shipToLine1)|Type the first line of the customer's shipping address.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[shipToLine2](#shipToLine2)|Type the second line of the customer's shipping address.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[shipToLine3](#shipToLine3)|Type the third line of the shipping address.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[shipToName](#shipToName)|Type a name for the customer's shipping address, such as "Headquarters" or "Field office",  to identify the address.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[shipToPostalCode](#shipToPostalCode)|Type the ZIP Code or postal code for the shipping address.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[shipToStateOrProvince](#shipToStateOrProvince)|Type the state or province for the shipping address.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[shipToTelephone](#shipToTelephone)|Type the phone number for the customer's shipping address.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[tax](#tax)|Type the tax amount for the quote product.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[taxBase](#taxBase)|Value of the Tax in base currency.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[uoMId](#uoMId)|Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[volumeDiscountAmount](#volumeDiscountAmount)|Shows the discount amount per unit if a specified volume is purchased. Configure volume discounts in the Product Catalog in the Settings area.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[volumeDiscountAmountBase](#volumeDiscountAmountBase)|Value of the Volume Discount in base currency.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[willCall](#willCall)|Select whether the quote product should be shipped to the specified address or held until the customer calls with further pick up or delivery instructions.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[sequenceNumber](#sequenceNumber)|Unique identifier of the data that maintains the sequence.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[propertyConfigurationStatus](#propertyConfigurationStatus)|Status of the property configuration.|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[propertyConfigurationStatus_display](#propertyConfigurationStatus_display)||<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[quoteDetailName](#quoteDetailName)|Quote Detail Name. Added for 1:n Referential relationship|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[parentBundleIdRef](#parentBundleIdRef)|Choose the parent bundle associated with this product|<a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>|
|[billingMethod](#billingMethod)|Billing method for the project quote line. Valid values are Time and Material and Fixed Price|<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|
|[billingMethod_display](#billingMethod_display)||<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|
|[billingStartDate](#billingStartDate)|Enter the estimated start date for the billing frequency on the project.|<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|
|[budgetAmount](#budgetAmount)|Enter the amount the customer has set aside or is willing to pay for the quote component.|<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|
|[budgetAmountBase](#budgetAmountBase)|Value of the Budget Amount in base currency.|<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|
|[costAmount](#costAmount)|Shows the total cost price of the product based on the cost price per unit and quantity.|<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|
|[costAmountBase](#costAmountBase)|Value of the CostAmount in base currency.|<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|
|[costPricePerUnit](#costPricePerUnit)|Cost per unit of the product. The default is the cost price of the product.|<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|
|[costPricePerUnitBase](#costPricePerUnitBase)|Value of the Cost Price Per Unit in base currency.|<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|
|[includeExpense](#includeExpense)|Select whether to include expenses in the quote line.|<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|
|[includeFee](#includeFee)|Select whether to include fees in the quote line.|<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|
|[includeMaterial](#includeMaterial)|Select whether to include materials in the quote line.|<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|
|[includeTime](#includeTime)|Select whether to include time transactions in the quote line.|<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|
|[invoiceFrequency](#invoiceFrequency)|Select the frequency for the automatic invoice creation job to create the invoice.|<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|
|[lineType](#lineType)|The field to distinguish the quote lines to be of project service or field service|<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|
|[lineType_display](#lineType_display)||<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|
|[opportunityLine](#opportunityLine)|Shows the opportunity line related to this quote line.|<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|
|[project](#project)|Select the project related to this quote line.|<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|
|[quoteLineDescription](#quoteLineDescription)|abstracts description for product based lines vs write-in products or project based lines|<a href="QuoteProduct.md" target="_blank">projectServiceAutomation/QuoteProduct</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#quoteDetailId name="quoteDetailId">quoteDetailId</a>

Unique identifier of the product line item in the quote.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote Product</td></tr><tr><td>description</td><td>Unique identifier of the product line item in the quote.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>quotedetailid</td></tr></table>

### <a href=#baseAmount name="baseAmount">baseAmount</a>

Shows the total price of the quote product, based on the price per unit, volume discount, and quantity.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount</td></tr><tr><td>description</td><td>Shows the total price of the quote product, based on the price per unit, volume discount, and quantity.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>baseamount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#baseAmountBase name="baseAmountBase">baseAmountBase</a>

Value of the Amount in base currency.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base)</td></tr><tr><td>description</td><td>Value of the Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>baseamount_base</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the quote product, such as manufacturing details or acceptable substitutions.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the quote product, such as manufacturing details or acceptable substitutions.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#extendedAmount name="extendedAmount">extendedAmount</a>

Shows the total amount due for the quote product, based on the sum of the unit price, quantity, discounts ,and tax.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Extended Amount</td></tr><tr><td>description</td><td>Shows the total amount due for the quote product, based on the sum of the unit price, quantity, discounts ,and tax.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>extendedamount</td></tr></table>

### <a href=#extendedAmountBase name="extendedAmountBase">extendedAmountBase</a>

Value of the Extended Amount in base currency.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Extended Amount (Base)</td></tr><tr><td>description</td><td>Value of the Extended Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>extendedamount_base</td></tr></table>

### <a href=#isPriceOverridden name="isPriceOverridden">isPriceOverridden</a>

Select whether the price per unit is fixed at the value in the specified price list or can be overridden by users who have edit rights to the quote product.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price Overridden</td></tr><tr><td>description</td><td>Select whether the price per unit is fixed at the value in the specified price list or can be overridden by users who have edit rights to the quote product.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ispriceoverridden</td></tr></table>

### <a href=#isProductOverridden name="isProductOverridden">isProductOverridden</a>

Select whether the product exists in the Microsoft Dynamics 365 product catalog or is a write-in product specific to the quote.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Select Product</td></tr><tr><td>description</td><td>Select whether the product exists in the Microsoft Dynamics 365 product catalog or is a write-in product specific to the quote.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isproductoverridden</td></tr></table>

### <a href=#lineItemNumber name="lineItemNumber">lineItemNumber</a>

Type the line item number for the quote product to easily identify the product in the quote and make sure it's listed in the correct order.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line Item Number</td></tr><tr><td>description</td><td>Type the line item number for the quote product to easily identify the product in the quote and make sure it's listed in the correct order.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lineitemnumber</td></tr></table>

### <a href=#manualDiscountAmount name="manualDiscountAmount">manualDiscountAmount</a>

Type the manual discount amount for the quote product to deduct any negotiated or other savings from the product total on the quote.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manual Discount</td></tr><tr><td>description</td><td>Type the manual discount amount for the quote product to deduct any negotiated or other savings from the product total on the quote.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>manualdiscountamount</td></tr></table>

### <a href=#manualDiscountAmountBase name="manualDiscountAmountBase">manualDiscountAmountBase</a>

Value of the Manual Discount in base currency.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manual Discount (Base)</td></tr><tr><td>description</td><td>Value of the Manual Discount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>manualdiscountamount_base</td></tr></table>

### <a href=#parentBundleId name="parentBundleId">parentBundleId</a>

Choose the parent bundle associated with this product  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Bundle</td></tr><tr><td>description</td><td>Choose the parent bundle associated with this product</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentbundleid</td></tr></table>

### <a href=#productAssociationId name="productAssociationId">productAssociationId</a>

Unique identifier of the product line item association with bundle in the quote  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bundle Item Association</td></tr><tr><td>description</td><td>Unique identifier of the product line item association with bundle in the quote</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>productassociationid</td></tr></table>

### <a href=#productTypeCode name="productTypeCode">productTypeCode</a>

Product Type  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product type</td></tr><tr><td>description</td><td>Product Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>producttypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Product</td><td>1</td></tr><tr><td>en</td><td>Bundle</td><td>2</td></tr><tr><td>en</td><td>Required Bundle Product</td><td>3</td></tr><tr><td>en</td><td>Optional Bundle Product</td><td>4</td></tr><tr><td>en</td><td>Project-based Service</td><td>5</td></tr></table></td></tr></table>

### <a href=#productTypeCode_display name="productTypeCode_display">productTypeCode_display</a>

First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#pricePerUnit name="pricePerUnit">pricePerUnit</a>

Type the price per unit of the quote product. The default is to the value in the price list specified on the quote for existing products.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price Per Unit</td></tr><tr><td>description</td><td>Type the price per unit of the quote product. The default is to the value in the price list specified on the quote for existing products.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>priceperunit</td></tr></table>

### <a href=#pricePerUnitBase name="pricePerUnitBase">pricePerUnitBase</a>

Value of the Price Per Unit in base currency.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price Per Unit (Base)</td></tr><tr><td>description</td><td>Value of the Price Per Unit in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>priceperunit_base</td></tr></table>

### <a href=#pricingErrorCode name="pricingErrorCode">pricingErrorCode</a>

Select the type of pricing error, such as a missing or invalid product, or missing quantity.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pricing Error </td></tr><tr><td>description</td><td>Select the type of pricing error, such as a missing or invalid product, or missing quantity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>pricingerrorcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>0</td></tr><tr><td>en</td><td>Detail Error</td><td>1</td></tr><tr><td>en</td><td>Missing Price Level</td><td>2</td></tr><tr><td>en</td><td>Inactive Price Level</td><td>3</td></tr><tr><td>en</td><td>Missing Quantity</td><td>4</td></tr><tr><td>en</td><td>Missing Unit Price</td><td>5</td></tr><tr><td>en</td><td>Missing Product</td><td>6</td></tr><tr><td>en</td><td>Invalid Product</td><td>7</td></tr><tr><td>en</td><td>Missing Pricing Code</td><td>8</td></tr><tr><td>en</td><td>Invalid Pricing Code</td><td>9</td></tr><tr><td>en</td><td>Missing UOM</td><td>10</td></tr><tr><td>en</td><td>Product Not In Price Level</td><td>11</td></tr><tr><td>en</td><td>Missing Price Level Amount</td><td>12</td></tr><tr><td>en</td><td>Missing Price Level Percentage</td><td>13</td></tr><tr><td>en</td><td>Missing Price</td><td>14</td></tr><tr><td>en</td><td>Missing Current Cost</td><td>15</td></tr><tr><td>en</td><td>Missing Standard Cost</td><td>16</td></tr><tr><td>en</td><td>Invalid Price Level Amount</td><td>17</td></tr><tr><td>en</td><td>Invalid Price Level Percentage</td><td>18</td></tr><tr><td>en</td><td>Invalid Price</td><td>19</td></tr><tr><td>en</td><td>Invalid Current Cost</td><td>20</td></tr><tr><td>en</td><td>Invalid Standard Cost</td><td>21</td></tr><tr><td>en</td><td>Invalid Rounding Policy</td><td>22</td></tr><tr><td>en</td><td>Invalid Rounding Option</td><td>23</td></tr><tr><td>en</td><td>Invalid Rounding Amount</td><td>24</td></tr><tr><td>en</td><td>Price Calculation Error</td><td>25</td></tr><tr><td>en</td><td>Invalid Discount Type</td><td>26</td></tr><tr><td>en</td><td>Discount Type Invalid State</td><td>27</td></tr><tr><td>en</td><td>Invalid Discount</td><td>28</td></tr><tr><td>en</td><td>Invalid Quantity</td><td>29</td></tr><tr><td>en</td><td>Invalid Pricing Precision</td><td>30</td></tr><tr><td>en</td><td>Missing Product Default UOM</td><td>31</td></tr><tr><td>en</td><td>Missing Product UOM Schedule </td><td>32</td></tr><tr><td>en</td><td>Inactive Discount Type</td><td>33</td></tr><tr><td>en</td><td>Invalid Price Level Currency</td><td>34</td></tr><tr><td>en</td><td>Price Attribute Out Of Range</td><td>35</td></tr><tr><td>en</td><td>Base Currency Attribute Overflow</td><td>36</td></tr><tr><td>en</td><td>Base Currency Attribute Underflow</td><td>37</td></tr></table></td></tr></table>

### <a href=#pricingErrorCode_display name="pricingErrorCode_display">pricingErrorCode_display</a>

First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#productDescription name="productDescription">productDescription</a>

Type a name or description to identify the type of write-in product included in the quote.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Write-In Product</td></tr><tr><td>description</td><td>Type a name or description to identify the type of write-in product included in the quote.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>productdescription</td></tr></table>

### <a href=#productName name="productName">productName</a>

Calculated field that will be populated by name and description of the product.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product Name</td></tr><tr><td>description</td><td>Calculated field that will be populated by name and description of the product.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>productname</td></tr></table>

### <a href=#productId name="productId">productId</a>

Choose the product to include on the quote to link the product's pricing and other information to the quote.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Existing Product</td></tr><tr><td>description</td><td>Choose the product to include on the quote to link the product's pricing and other information to the quote.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>productid</td></tr></table>

### <a href=#quantity name="quantity">quantity</a>

Type the amount or quantity of the product requested by the customer.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity</td></tr><tr><td>description</td><td>Type the amount or quantity of the product requested by the customer.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>quantity</td></tr></table>

### <a href=#quoteId name="quoteId">quoteId</a>

Unique identifier of the quote for the quote product.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote</td></tr><tr><td>description</td><td>Unique identifier of the quote for the quote product.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>quoteid</td></tr></table>

### <a href=#quoteStateCode name="quoteStateCode">quoteStateCode</a>

Status of the quote product.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote Status</td></tr><tr><td>description</td><td>Status of the quote product.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>quotestatecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#quoteStateCode_display name="quoteStateCode_display">quoteStateCode_display</a>

First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#requestDeliveryBy name="requestDeliveryBy">requestDeliveryBy</a>

Enter the delivery date requested by the customer for the quote product.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requested Delivery Date</td></tr><tr><td>description</td><td>Enter the delivery date requested by the customer for the quote product.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>requestdeliveryby</td></tr></table>

### <a href=#salesRepId name="salesRepId">salesRepId</a>

Choose the user responsible for the sale of the quote product.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Salesperson</td></tr><tr><td>description</td><td>Choose the user responsible for the sale of the quote product.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>salesrepid</td></tr></table>

### <a href=#shipToAddressId name="shipToAddressId">shipToAddressId</a>

Unique identifier of the shipping address.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Address ID</td></tr><tr><td>description</td><td>Unique identifier of the shipping address.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_addressid</td></tr></table>

### <a href=#shipToCity name="shipToCity">shipToCity</a>

Type the city for the customer's shipping address.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To City</td></tr><tr><td>description</td><td>Type the city for the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_city</td></tr></table>

### <a href=#shipToContactName name="shipToContactName">shipToContactName</a>

Type the primary contact name at the customer's shipping address.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Contact Name</td></tr><tr><td>description</td><td>Type the primary contact name at the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_contactname</td></tr></table>

### <a href=#shipToCountry name="shipToCountry">shipToCountry</a>

Type the country or region for the customer's shipping address.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Country/Region</td></tr><tr><td>description</td><td>Type the country or region for the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_country</td></tr></table>

### <a href=#shipToFax name="shipToFax">shipToFax</a>

Type the fax number for the customer's shipping address.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Fax</td></tr><tr><td>description</td><td>Type the fax number for the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_fax</td></tr></table>

### <a href=#shipToFreightTermsCode name="shipToFreightTermsCode">shipToFreightTermsCode</a>

Select the freight terms to make sure shipping orders are processed correctly.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freight Terms</td></tr><tr><td>description</td><td>Select the freight terms to make sure shipping orders are processed correctly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_freighttermscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>FOB</td><td>1</td></tr><tr><td>en</td><td>No Charge</td><td>2</td></tr></table></td></tr></table>

### <a href=#shipToFreightTermsCode_display name="shipToFreightTermsCode_display">shipToFreightTermsCode_display</a>

First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#shipToLine1 name="shipToLine1">shipToLine1</a>

Type the first line of the customer's shipping address.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Street 1</td></tr><tr><td>description</td><td>Type the first line of the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_line1</td></tr></table>

### <a href=#shipToLine2 name="shipToLine2">shipToLine2</a>

Type the second line of the customer's shipping address.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Street 2</td></tr><tr><td>description</td><td>Type the second line of the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_line2</td></tr></table>

### <a href=#shipToLine3 name="shipToLine3">shipToLine3</a>

Type the third line of the shipping address.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Street 3</td></tr><tr><td>description</td><td>Type the third line of the shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_line3</td></tr></table>

### <a href=#shipToName name="shipToName">shipToName</a>

Type a name for the customer's shipping address, such as "Headquarters" or "Field office",  to identify the address.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Name</td></tr><tr><td>description</td><td>Type a name for the customer's shipping address, such as "Headquarters" or "Field office",  to identify the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_name</td></tr></table>

### <a href=#shipToPostalCode name="shipToPostalCode">shipToPostalCode</a>

Type the ZIP Code or postal code for the shipping address.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To ZIP/Postal Code</td></tr><tr><td>description</td><td>Type the ZIP Code or postal code for the shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_postalcode</td></tr></table>

### <a href=#shipToStateOrProvince name="shipToStateOrProvince">shipToStateOrProvince</a>

Type the state or province for the shipping address.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To State/Province</td></tr><tr><td>description</td><td>Type the state or province for the shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_stateorprovince</td></tr></table>

### <a href=#shipToTelephone name="shipToTelephone">shipToTelephone</a>

Type the phone number for the customer's shipping address.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Phone</td></tr><tr><td>description</td><td>Type the phone number for the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_telephone</td></tr></table>

### <a href=#tax name="tax">tax</a>

Type the tax amount for the quote product.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax</td></tr><tr><td>description</td><td>Type the tax amount for the quote product.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>-1000000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>tax</td></tr></table>

### <a href=#taxBase name="taxBase">taxBase</a>

Value of the Tax in base currency.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax (Base)</td></tr><tr><td>description</td><td>Value of the Tax in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>tax_base</td></tr></table>

### <a href=#uoMId name="uoMId">uoMId</a>

Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit</td></tr><tr><td>description</td><td>Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>uomid</td></tr></table>

### <a href=#volumeDiscountAmount name="volumeDiscountAmount">volumeDiscountAmount</a>

Shows the discount amount per unit if a specified volume is purchased. Configure volume discounts in the Product Catalog in the Settings area.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Volume Discount</td></tr><tr><td>description</td><td>Shows the discount amount per unit if a specified volume is purchased. Configure volume discounts in the Product Catalog in the Settings area.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>volumediscountamount</td></tr></table>

### <a href=#volumeDiscountAmountBase name="volumeDiscountAmountBase">volumeDiscountAmountBase</a>

Value of the Volume Discount in base currency.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Volume Discount (Base)</td></tr><tr><td>description</td><td>Value of the Volume Discount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>volumediscountamount_base</td></tr></table>

### <a href=#willCall name="willCall">willCall</a>

Select whether the quote product should be shipped to the specified address or held until the customer calls with further pick up or delivery instructions.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To</td></tr><tr><td>description</td><td>Select whether the quote product should be shipped to the specified address or held until the customer calls with further pick up or delivery instructions.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>willcall</td></tr></table>

### <a href=#sequenceNumber name="sequenceNumber">sequenceNumber</a>

Unique identifier of the data that maintains the sequence.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data that maintains the sequence.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sequencenumber</td></tr></table>

### <a href=#propertyConfigurationStatus name="propertyConfigurationStatus">propertyConfigurationStatus</a>

Status of the property configuration.  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Property Configuration</td></tr><tr><td>description</td><td>Status of the property configuration.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>propertyconfigurationstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Edit</td><td>0</td></tr><tr><td>en</td><td>Rectify</td><td>1</td></tr><tr><td>en</td><td>Not Configured</td><td>2</td></tr></table></td></tr></table>

### <a href=#propertyConfigurationStatus_display name="propertyConfigurationStatus_display">propertyConfigurationStatus_display</a>

First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#quoteDetailName name="quoteDetailName">quoteDetailName</a>

Quote Detail Name. Added for 1:n Referential relationship  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Quote Detail Name. Added for 1:n Referential relationship</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>quotedetailname</td></tr></table>

### <a href=#parentBundleIdRef name="parentBundleIdRef">parentBundleIdRef</a>

Choose the parent bundle associated with this product  
First included in: <a href="../../sales/QuoteProduct.md" target="_blank">sales/QuoteProduct</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent bundle product</td></tr><tr><td>description</td><td>Choose the parent bundle associated with this product</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentbundleidref</td></tr></table>

### <a href=#billingMethod name="billingMethod">billingMethod</a>

Billing method for the project quote line. Valid values are Time and Material and Fixed Price  
First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing Method</td></tr><tr><td>description</td><td>Billing method for the project quote line. Valid values are Time and Material and Fixed Price</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_billingmethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Time and Material</td><td>192350000</td></tr><tr><td>en</td><td>Fixed Price</td><td>192350001</td></tr></table></td></tr></table>

### <a href=#billingMethod_display name="billingMethod_display">billingMethod_display</a>

First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#billingStartDate name="billingStartDate">billingStartDate</a>

Enter the estimated start date for the billing frequency on the project.  
First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Billing Start Date</td></tr><tr><td>description</td><td>Enter the estimated start date for the billing frequency on the project.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_billingstartdate</td></tr></table>

### <a href=#budgetAmount name="budgetAmount">budgetAmount</a>

Enter the amount the customer has set aside or is willing to pay for the quote component.  
First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Budget</td></tr><tr><td>description</td><td>Enter the amount the customer has set aside or is willing to pay for the quote component.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_budgetamount</td></tr></table>

### <a href=#budgetAmountBase name="budgetAmountBase">budgetAmountBase</a>

Value of the Budget Amount in base currency.  
First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget Amount (Base)</td></tr><tr><td>description</td><td>Value of the Budget Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_budgetamount_base</td></tr></table>

### <a href=#costAmount name="costAmount">costAmount</a>

Shows the total cost price of the product based on the cost price per unit and quantity.  
First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Amount</td></tr><tr><td>description</td><td>Shows the total cost price of the product based on the cost price per unit and quantity.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costamount</td></tr></table>

### <a href=#costAmountBase name="costAmountBase">costAmountBase</a>

Value of the CostAmount in base currency.  
First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CostAmount (Base)</td></tr><tr><td>description</td><td>Value of the CostAmount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costamount_base</td></tr></table>

### <a href=#costPricePerUnit name="costPricePerUnit">costPricePerUnit</a>

Cost per unit of the product. The default is the cost price of the product.  
First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Per Unit</td></tr><tr><td>description</td><td>Cost per unit of the product. The default is the cost price of the product.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costpriceperunit</td></tr></table>

### <a href=#costPricePerUnitBase name="costPricePerUnitBase">costPricePerUnitBase</a>

Value of the Cost Price Per Unit in base currency.  
First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost Price Per Unit (Base)</td></tr><tr><td>description</td><td>Value of the Cost Price Per Unit in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_costpriceperunit_base</td></tr></table>

### <a href=#includeExpense name="includeExpense">includeExpense</a>

Select whether to include expenses in the quote line.  
First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include Expense</td></tr><tr><td>description</td><td>Select whether to include expenses in the quote line.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_includeexpense</td></tr></table>

### <a href=#includeFee name="includeFee">includeFee</a>

Select whether to include fees in the quote line.  
First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include Fee</td></tr><tr><td>description</td><td>Select whether to include fees in the quote line.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_includefee</td></tr></table>

### <a href=#includeMaterial name="includeMaterial">includeMaterial</a>

Select whether to include materials in the quote line.  
First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include Material</td></tr><tr><td>description</td><td>Select whether to include materials in the quote line.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_includematerial</td></tr></table>

### <a href=#includeTime name="includeTime">includeTime</a>

Select whether to include time transactions in the quote line.  
First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include Time</td></tr><tr><td>description</td><td>Select whether to include time transactions in the quote line.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_includetime</td></tr></table>

### <a href=#invoiceFrequency name="invoiceFrequency">invoiceFrequency</a>

Select the frequency for the automatic invoice creation job to create the invoice.  
First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Frequency</td></tr><tr><td>description</td><td>Select the frequency for the automatic invoice creation job to create the invoice.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_invoicefrequency</td></tr></table>

### <a href=#lineType name="lineType">lineType</a>

The field to distinguish the quote lines to be of project service or field service  
First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line Type</td></tr><tr><td>description</td><td>The field to distinguish the quote lines to be of project service or field service</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_linetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Project Service Line</td><td>690970000</td></tr><tr><td>en</td><td>Field Service Line</td><td>690970001</td></tr></table></td></tr></table>

### <a href=#lineType_display name="lineType_display">lineType_display</a>

First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#opportunityLine name="opportunityLine">opportunityLine</a>

Shows the opportunity line related to this quote line.  
First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Opportunity Line</td></tr><tr><td>description</td><td>Shows the opportunity line related to this quote line.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_opportunityline</td></tr></table>

### <a href=#project name="project">project</a>

Select the project related to this quote line.  
First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Project</td></tr><tr><td>description</td><td>Select the project related to this quote line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_project</td></tr></table>

### <a href=#quoteLineDescription name="quoteLineDescription">quoteLineDescription</a>

abstracts description for product based lines vs write-in products or project based lines  
First included in: projectServiceAutomation/QuoteProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote Line Description</td></tr><tr><td>description</td><td>abstracts description for product based lines vs write-in products or project based lines</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_linedescription</td></tr></table>
