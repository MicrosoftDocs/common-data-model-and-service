---
title: InvoiceProduct - Common Data Model | Microsoft Docs
description: Line item in an invoice containing detailed billing information for a product.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Invoice Product

Line item in an invoice containing detailed billing information for a product.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/sales/InvoiceProduct.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/sales/InvoiceProduct  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[ownerId](#ownerId)|Owner Id|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[invoiceDetailId](#invoiceDetailId)|Unique identifier of the invoice product line item.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[actualDeliveryOn](#actualDeliveryOn)|Enter the date when the invoiced product was delivered to the customer.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[baseAmount](#baseAmount)|Shows the total price of the invoice product, based on the price per unit, volume discount, and quantity.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[baseAmountBase](#baseAmountBase)|Value of the Amount in base currency.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[description](#description)|Type additional information to describe the product line item of the invoice.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[extendedAmount](#extendedAmount)|Shows the total amount due for the invoice product, based on the sum of the unit price, quantity, discounts, and tax.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[extendedAmountBase](#extendedAmountBase)|Value of the Extended Amount in base currency.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[invoiceId](#invoiceId)|Unique identifier of the invoice associated with the invoice product line item.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[invoiceIsPriceLocked](#invoiceIsPriceLocked)|Information about whether invoice product pricing is locked.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[invoiceStateCode](#invoiceStateCode)|Status of the invoice product.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[invoiceStateCode_display](#invoiceStateCode_display)||<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[isCopied](#isCopied)|Select whether the invoice product is copied from another item or data source.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[isPriceOverridden](#isPriceOverridden)|Select whether the price per unit is fixed at the value in the specified price list or can be overridden by users who have edit rights to the invoice product.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[isProductOverridden](#isProductOverridden)|Select whether the product exists in the Microsoft Dynamics 365 product catalog or is a write-in product specific to the parent invoice.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[lineItemNumber](#lineItemNumber)|Type the line item number for the invoice product to easily identify the product in the invoice and make sure it's listed in the correct order.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[manualDiscountAmount](#manualDiscountAmount)|Type the manual discount amount for the invoice product to deduct any negotiated or other savings from the product total.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[manualDiscountAmountBase](#manualDiscountAmountBase)|Value of the Manual Discount in base currency.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[parentBundleId](#parentBundleId)|Choose the parent bundle associated with this product|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[productAssociationId](#productAssociationId)|Unique identifier of the product line item association with bundle in the invoice|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[productTypeCode](#productTypeCode)|Product Type|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[productTypeCode_display](#productTypeCode_display)||<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[pricePerUnit](#pricePerUnit)|Type the price per unit of the invoice product. The default is the value in the price list specified on the parent invoice for existing products.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[pricePerUnitBase](#pricePerUnitBase)|Value of the Price Per Unit in base currency.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[pricingErrorCode](#pricingErrorCode)|Pricing error for the invoice product line item.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[pricingErrorCode_display](#pricingErrorCode_display)||<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[productDescription](#productDescription)|Type a name or description to identify the type of write-in product included in the invoice.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[productName](#productName)|Calculated field that will be populated by name and description of the product.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[productId](#productId)|Choose the product to include on the invoice.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[quantity](#quantity)|Type the amount or quantity of the product included in the invoice's total amount due.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[quantityBackordered](#quantityBackordered)|Type the amount or quantity of the product that is back ordered for the invoice.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[quantityCancelled](#quantityCancelled)|Type the amount or quantity of the product that was canceled for the invoice line item.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[quantityShipped](#quantityShipped)|Type the amount or quantity of the product that was shipped.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[salesRepId](#salesRepId)|Choose the user responsible for the sale of the invoice product.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[shippingTrackingNumber](#shippingTrackingNumber)|Type a tracking number for shipment of the invoiced product.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[shipToCity](#shipToCity)|Type the city for the customer's shipping address.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[shipToCountry](#shipToCountry)|Type the country or region for the customer's shipping address.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[shipToFax](#shipToFax)|Type the fax number for the customer's shipping address.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[shipToFreightTermsCode](#shipToFreightTermsCode)|Select the freight terms to make sure shipping orders are processed correctly.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[shipToFreightTermsCode_display](#shipToFreightTermsCode_display)||<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[shipToLine1](#shipToLine1)|Type the first line of the customer's shipping address.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[shipToLine2](#shipToLine2)|Type the second line of the customer's shipping address.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[shipToLine3](#shipToLine3)|Type the third line of the shipping address.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[shipToName](#shipToName)|Type a name for the customer's shipping address, such as "Headquarters" or "Field office",  to identify the address.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[shipToPostalCode](#shipToPostalCode)|Type the ZIP Code or postal code for the shipping address.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[shipToStateOrProvince](#shipToStateOrProvince)|Type the state or province for the shipping address.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[shipToTelephone](#shipToTelephone)|Type the phone number for the customer's shipping address.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[tax](#tax)|Type the tax amount for the invoice product.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[taxBase](#taxBase)|Value of the Tax in base currency.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[uoMId](#uoMId)|Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[volumeDiscountAmount](#volumeDiscountAmount)|Shows the discount amount per unit if a specified volume is purchased. Configure volume discounts in the Product Catalog in the Settings area.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[volumeDiscountAmountBase](#volumeDiscountAmountBase)|Value of the Volume Discount in base currency.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[willCall](#willCall)|Select whether the invoice product should be shipped to the specified address or held until the customer calls with further pick up or delivery instructions.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[sequenceNumber](#sequenceNumber)|Shows the ID of the data that maintains the sequence.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[propertyConfigurationStatus](#propertyConfigurationStatus)|Status of the property configuration.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[propertyConfigurationStatus_display](#propertyConfigurationStatus_display)||<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[invoiceDetailName](#invoiceDetailName)|Invoice Detail Name. Added for 1:n Referential relationship|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[salesOrderDetailId](#salesOrderDetailId)|Unique identifier for Order Line associated with Invoice Line.|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|
|[parentBundleIdRef](#parentBundleIdRef)|Choose the parent bundle associated with this product|<a href="InvoiceProduct.md" target="_blank">sales/InvoiceProduct</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#invoiceDetailId name="invoiceDetailId">invoiceDetailId</a>

Unique identifier of the invoice product line item.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Product</td></tr><tr><td>description</td><td>Unique identifier of the invoice product line item.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>invoicedetailid</td></tr></table>

### <a href=#actualDeliveryOn name="actualDeliveryOn">actualDeliveryOn</a>

Enter the date when the invoiced product was delivered to the customer.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivered On</td></tr><tr><td>description</td><td>Enter the date when the invoiced product was delivered to the customer.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualdeliveryon</td></tr></table>

### <a href=#baseAmount name="baseAmount">baseAmount</a>

Shows the total price of the invoice product, based on the price per unit, volume discount, and quantity.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount</td></tr><tr><td>description</td><td>Shows the total price of the invoice product, based on the price per unit, volume discount, and quantity.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>baseamount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#baseAmountBase name="baseAmountBase">baseAmountBase</a>

Value of the Amount in base currency.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount (Base)</td></tr><tr><td>description</td><td>Value of the Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>baseamount_base</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the product line item of the invoice.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the product line item of the invoice.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#extendedAmount name="extendedAmount">extendedAmount</a>

Shows the total amount due for the invoice product, based on the sum of the unit price, quantity, discounts, and tax.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Extended Amount</td></tr><tr><td>description</td><td>Shows the total amount due for the invoice product, based on the sum of the unit price, quantity, discounts, and tax.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>extendedamount</td></tr></table>

### <a href=#extendedAmountBase name="extendedAmountBase">extendedAmountBase</a>

Value of the Extended Amount in base currency.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Extended Amount (Base)</td></tr><tr><td>description</td><td>Value of the Extended Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>extendedamount_base</td></tr></table>

### <a href=#invoiceId name="invoiceId">invoiceId</a>

Unique identifier of the invoice associated with the invoice product line item.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice ID</td></tr><tr><td>description</td><td>Unique identifier of the invoice associated with the invoice product line item.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>invoiceid</td></tr></table>

### <a href=#invoiceIsPriceLocked name="invoiceIsPriceLocked">invoiceIsPriceLocked</a>

Information about whether invoice product pricing is locked.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Is Price Locked</td></tr><tr><td>description</td><td>Information about whether invoice product pricing is locked.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>invoiceispricelocked</td></tr></table>

### <a href=#invoiceStateCode name="invoiceStateCode">invoiceStateCode</a>

Status of the invoice product.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Status</td></tr><tr><td>description</td><td>Status of the invoice product.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>invoicestatecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#invoiceStateCode_display name="invoiceStateCode_display">invoiceStateCode_display</a>

First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isCopied name="isCopied">isCopied</a>

Select whether the invoice product is copied from another item or data source.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Copied</td></tr><tr><td>description</td><td>Select whether the invoice product is copied from another item or data source.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>iscopied</td></tr></table>

### <a href=#isPriceOverridden name="isPriceOverridden">isPriceOverridden</a>

Select whether the price per unit is fixed at the value in the specified price list or can be overridden by users who have edit rights to the invoice product.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pricing</td></tr><tr><td>description</td><td>Select whether the price per unit is fixed at the value in the specified price list or can be overridden by users who have edit rights to the invoice product.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ispriceoverridden</td></tr></table>

### <a href=#isProductOverridden name="isProductOverridden">isProductOverridden</a>

Select whether the product exists in the Microsoft Dynamics 365 product catalog or is a write-in product specific to the parent invoice.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Select Product</td></tr><tr><td>description</td><td>Select whether the product exists in the Microsoft Dynamics 365 product catalog or is a write-in product specific to the parent invoice.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isproductoverridden</td></tr></table>

### <a href=#lineItemNumber name="lineItemNumber">lineItemNumber</a>

Type the line item number for the invoice product to easily identify the product in the invoice and make sure it's listed in the correct order.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line Item Number</td></tr><tr><td>description</td><td>Type the line item number for the invoice product to easily identify the product in the invoice and make sure it's listed in the correct order.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lineitemnumber</td></tr></table>

### <a href=#manualDiscountAmount name="manualDiscountAmount">manualDiscountAmount</a>

Type the manual discount amount for the invoice product to deduct any negotiated or other savings from the product total.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manual Discount</td></tr><tr><td>description</td><td>Type the manual discount amount for the invoice product to deduct any negotiated or other savings from the product total.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>manualdiscountamount</td></tr></table>

### <a href=#manualDiscountAmountBase name="manualDiscountAmountBase">manualDiscountAmountBase</a>

Value of the Manual Discount in base currency.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manual Discount (Base)</td></tr><tr><td>description</td><td>Value of the Manual Discount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>manualdiscountamount_base</td></tr></table>

### <a href=#parentBundleId name="parentBundleId">parentBundleId</a>

Choose the parent bundle associated with this product  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Bundle</td></tr><tr><td>description</td><td>Choose the parent bundle associated with this product</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentbundleid</td></tr></table>

### <a href=#productAssociationId name="productAssociationId">productAssociationId</a>

Unique identifier of the product line item association with bundle in the invoice  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bundle Item Association</td></tr><tr><td>description</td><td>Unique identifier of the product line item association with bundle in the invoice</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>productassociationid</td></tr></table>

### <a href=#productTypeCode name="productTypeCode">productTypeCode</a>

Product Type  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product type</td></tr><tr><td>description</td><td>Product Type</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>producttypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Product</td><td>1</td></tr><tr><td>en</td><td>Bundle</td><td>2</td></tr><tr><td>en</td><td>Required Bundle Product</td><td>3</td></tr><tr><td>en</td><td>Optional Bundle Product</td><td>4</td></tr><tr><td>en</td><td>Project-based Service</td><td>5</td></tr></table></td></tr></table>

### <a href=#productTypeCode_display name="productTypeCode_display">productTypeCode_display</a>

First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#pricePerUnit name="pricePerUnit">pricePerUnit</a>

Type the price per unit of the invoice product. The default is the value in the price list specified on the parent invoice for existing products.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price Per Unit</td></tr><tr><td>description</td><td>Type the price per unit of the invoice product. The default is the value in the price list specified on the parent invoice for existing products.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>priceperunit</td></tr></table>

### <a href=#pricePerUnitBase name="pricePerUnitBase">pricePerUnitBase</a>

Value of the Price Per Unit in base currency.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price Per Unit (Base)</td></tr><tr><td>description</td><td>Value of the Price Per Unit in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>priceperunit_base</td></tr></table>

### <a href=#pricingErrorCode name="pricingErrorCode">pricingErrorCode</a>

Pricing error for the invoice product line item.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pricing Error </td></tr><tr><td>description</td><td>Pricing error for the invoice product line item.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>pricingerrorcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>0</td></tr><tr><td>en</td><td>Detail Error</td><td>1</td></tr><tr><td>en</td><td>Missing Price Level</td><td>2</td></tr><tr><td>en</td><td>Inactive Price Level</td><td>3</td></tr><tr><td>en</td><td>Missing Quantity</td><td>4</td></tr><tr><td>en</td><td>Missing Unit Price</td><td>5</td></tr><tr><td>en</td><td>Missing Product</td><td>6</td></tr><tr><td>en</td><td>Invalid Product</td><td>7</td></tr><tr><td>en</td><td>Missing Pricing Code</td><td>8</td></tr><tr><td>en</td><td>Invalid Pricing Code</td><td>9</td></tr><tr><td>en</td><td>Missing UOM</td><td>10</td></tr><tr><td>en</td><td>Product Not In Price Level</td><td>11</td></tr><tr><td>en</td><td>Missing Price Level Amount</td><td>12</td></tr><tr><td>en</td><td>Missing Price Level Percentage</td><td>13</td></tr><tr><td>en</td><td>Missing Price</td><td>14</td></tr><tr><td>en</td><td>Missing Current Cost</td><td>15</td></tr><tr><td>en</td><td>Missing Standard Cost</td><td>16</td></tr><tr><td>en</td><td>Invalid Price Level Amount</td><td>17</td></tr><tr><td>en</td><td>Invalid Price Level Percentage</td><td>18</td></tr><tr><td>en</td><td>Invalid Price</td><td>19</td></tr><tr><td>en</td><td>Invalid Current Cost</td><td>20</td></tr><tr><td>en</td><td>Invalid Standard Cost</td><td>21</td></tr><tr><td>en</td><td>Invalid Rounding Policy</td><td>22</td></tr><tr><td>en</td><td>Invalid Rounding Option</td><td>23</td></tr><tr><td>en</td><td>Invalid Rounding Amount</td><td>24</td></tr><tr><td>en</td><td>Price Calculation Error</td><td>25</td></tr><tr><td>en</td><td>Invalid Discount Type</td><td>26</td></tr><tr><td>en</td><td>Discount Type Invalid State</td><td>27</td></tr><tr><td>en</td><td>Invalid Discount</td><td>28</td></tr><tr><td>en</td><td>Invalid Quantity</td><td>29</td></tr><tr><td>en</td><td>Invalid Pricing Precision</td><td>30</td></tr><tr><td>en</td><td>Missing Product Default UOM</td><td>31</td></tr><tr><td>en</td><td>Missing Product UOM Schedule </td><td>32</td></tr><tr><td>en</td><td>Inactive Discount Type</td><td>33</td></tr><tr><td>en</td><td>Invalid Price Level Currency</td><td>34</td></tr><tr><td>en</td><td>Price Attribute Out Of Range</td><td>35</td></tr><tr><td>en</td><td>Base Currency Attribute Overflow</td><td>36</td></tr><tr><td>en</td><td>Base Currency Attribute Underflow</td><td>37</td></tr></table></td></tr></table>

### <a href=#pricingErrorCode_display name="pricingErrorCode_display">pricingErrorCode_display</a>

First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#productDescription name="productDescription">productDescription</a>

Type a name or description to identify the type of write-in product included in the invoice.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Write-In Product</td></tr><tr><td>description</td><td>Type a name or description to identify the type of write-in product included in the invoice.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>productdescription</td></tr></table>

### <a href=#productName name="productName">productName</a>

Calculated field that will be populated by name and description of the product.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product Name</td></tr><tr><td>description</td><td>Calculated field that will be populated by name and description of the product.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>productname</td></tr></table>

### <a href=#productId name="productId">productId</a>

Choose the product to include on the invoice.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Existing Product</td></tr><tr><td>description</td><td>Choose the product to include on the invoice.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>productid</td></tr></table>

### <a href=#quantity name="quantity">quantity</a>

Type the amount or quantity of the product included in the invoice's total amount due.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity</td></tr><tr><td>description</td><td>Type the amount or quantity of the product included in the invoice's total amount due.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>quantity</td></tr></table>

### <a href=#quantityBackordered name="quantityBackordered">quantityBackordered</a>

Type the amount or quantity of the product that is back ordered for the invoice.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity Back Ordered</td></tr><tr><td>description</td><td>Type the amount or quantity of the product that is back ordered for the invoice.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>quantitybackordered</td></tr></table>

### <a href=#quantityCancelled name="quantityCancelled">quantityCancelled</a>

Type the amount or quantity of the product that was canceled for the invoice line item.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity Canceled</td></tr><tr><td>description</td><td>Type the amount or quantity of the product that was canceled for the invoice line item.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>quantitycancelled</td></tr></table>

### <a href=#quantityShipped name="quantityShipped">quantityShipped</a>

Type the amount or quantity of the product that was shipped.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity Shipped</td></tr><tr><td>description</td><td>Type the amount or quantity of the product that was shipped.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>-1000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>quantityshipped</td></tr></table>

### <a href=#salesRepId name="salesRepId">salesRepId</a>

Choose the user responsible for the sale of the invoice product.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Salesperson</td></tr><tr><td>description</td><td>Choose the user responsible for the sale of the invoice product.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>salesrepid</td></tr></table>

### <a href=#shippingTrackingNumber name="shippingTrackingNumber">shippingTrackingNumber</a>

Type a tracking number for shipment of the invoiced product.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipment Tracking Number</td></tr><tr><td>description</td><td>Type a tracking number for shipment of the invoiced product.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shippingtrackingnumber</td></tr></table>

### <a href=#shipToCity name="shipToCity">shipToCity</a>

Type the city for the customer's shipping address.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To City</td></tr><tr><td>description</td><td>Type the city for the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_city</td></tr></table>

### <a href=#shipToCountry name="shipToCountry">shipToCountry</a>

Type the country or region for the customer's shipping address.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Country/Region</td></tr><tr><td>description</td><td>Type the country or region for the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_country</td></tr></table>

### <a href=#shipToFax name="shipToFax">shipToFax</a>

Type the fax number for the customer's shipping address.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Fax</td></tr><tr><td>description</td><td>Type the fax number for the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_fax</td></tr></table>

### <a href=#shipToFreightTermsCode name="shipToFreightTermsCode">shipToFreightTermsCode</a>

Select the freight terms to make sure shipping orders are processed correctly.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freight Terms</td></tr><tr><td>description</td><td>Select the freight terms to make sure shipping orders are processed correctly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_freighttermscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>FOB</td><td>1</td></tr><tr><td>en</td><td>No Charge</td><td>2</td></tr></table></td></tr></table>

### <a href=#shipToFreightTermsCode_display name="shipToFreightTermsCode_display">shipToFreightTermsCode_display</a>

First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#shipToLine1 name="shipToLine1">shipToLine1</a>

Type the first line of the customer's shipping address.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Street 1</td></tr><tr><td>description</td><td>Type the first line of the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_line1</td></tr></table>

### <a href=#shipToLine2 name="shipToLine2">shipToLine2</a>

Type the second line of the customer's shipping address.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Street 2</td></tr><tr><td>description</td><td>Type the second line of the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_line2</td></tr></table>

### <a href=#shipToLine3 name="shipToLine3">shipToLine3</a>

Type the third line of the shipping address.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Street 3</td></tr><tr><td>description</td><td>Type the third line of the shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_line3</td></tr></table>

### <a href=#shipToName name="shipToName">shipToName</a>

Type a name for the customer's shipping address, such as "Headquarters" or "Field office",  to identify the address.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Name</td></tr><tr><td>description</td><td>Type a name for the customer's shipping address, such as "Headquarters" or "Field office",  to identify the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_name</td></tr></table>

### <a href=#shipToPostalCode name="shipToPostalCode">shipToPostalCode</a>

Type the ZIP Code or postal code for the shipping address.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To ZIP/Postal Code</td></tr><tr><td>description</td><td>Type the ZIP Code or postal code for the shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_postalcode</td></tr></table>

### <a href=#shipToStateOrProvince name="shipToStateOrProvince">shipToStateOrProvince</a>

Type the state or province for the shipping address.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To State/Province</td></tr><tr><td>description</td><td>Type the state or province for the shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_stateorprovince</td></tr></table>

### <a href=#shipToTelephone name="shipToTelephone">shipToTelephone</a>

Type the phone number for the customer's shipping address.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Phone</td></tr><tr><td>description</td><td>Type the phone number for the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_telephone</td></tr></table>

### <a href=#tax name="tax">tax</a>

Type the tax amount for the invoice product.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax</td></tr><tr><td>description</td><td>Type the tax amount for the invoice product.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>-1000000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>tax</td></tr></table>

### <a href=#taxBase name="taxBase">taxBase</a>

Value of the Tax in base currency.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax (Base)</td></tr><tr><td>description</td><td>Value of the Tax in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>tax_base</td></tr></table>

### <a href=#uoMId name="uoMId">uoMId</a>

Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit</td></tr><tr><td>description</td><td>Choose the unit of measurement for the base unit quantity for this purchase, such as each or dozen.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>uomid</td></tr></table>

### <a href=#volumeDiscountAmount name="volumeDiscountAmount">volumeDiscountAmount</a>

Shows the discount amount per unit if a specified volume is purchased. Configure volume discounts in the Product Catalog in the Settings area.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Volume Discount</td></tr><tr><td>description</td><td>Shows the discount amount per unit if a specified volume is purchased. Configure volume discounts in the Product Catalog in the Settings area.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>volumediscountamount</td></tr></table>

### <a href=#volumeDiscountAmountBase name="volumeDiscountAmountBase">volumeDiscountAmountBase</a>

Value of the Volume Discount in base currency.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Volume Discount (Base)</td></tr><tr><td>description</td><td>Value of the Volume Discount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>volumediscountamount_base</td></tr></table>

### <a href=#willCall name="willCall">willCall</a>

Select whether the invoice product should be shipped to the specified address or held until the customer calls with further pick up or delivery instructions.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To</td></tr><tr><td>description</td><td>Select whether the invoice product should be shipped to the specified address or held until the customer calls with further pick up or delivery instructions.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>willcall</td></tr></table>

### <a href=#sequenceNumber name="sequenceNumber">sequenceNumber</a>

Shows the ID of the data that maintains the sequence.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sequence Number</td></tr><tr><td>description</td><td>Shows the ID of the data that maintains the sequence.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sequencenumber</td></tr></table>

### <a href=#propertyConfigurationStatus name="propertyConfigurationStatus">propertyConfigurationStatus</a>

Status of the property configuration.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Property Configuration</td></tr><tr><td>description</td><td>Status of the property configuration.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>propertyconfigurationstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Edit</td><td>0</td></tr><tr><td>en</td><td>Rectify</td><td>1</td></tr><tr><td>en</td><td>Not Configured</td><td>2</td></tr></table></td></tr></table>

### <a href=#propertyConfigurationStatus_display name="propertyConfigurationStatus_display">propertyConfigurationStatus_display</a>

First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#invoiceDetailName name="invoiceDetailName">invoiceDetailName</a>

Invoice Detail Name. Added for 1:n Referential relationship  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Invoice Detail Name. Added for 1:n Referential relationship</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>invoicedetailname</td></tr></table>

### <a href=#salesOrderDetailId name="salesOrderDetailId">salesOrderDetailId</a>

Unique identifier for Order Line associated with Invoice Line.  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Order Product Id</td></tr><tr><td>description</td><td>Unique identifier for Order Line associated with Invoice Line.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>salesorderdetailid</td></tr></table>

### <a href=#parentBundleIdRef name="parentBundleIdRef">parentBundleIdRef</a>

Choose the parent bundle associated with this product  
First included in: sales/InvoiceProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent bundle product</td></tr><tr><td>description</td><td>Choose the parent bundle associated with this product</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentbundleidref</td></tr></table>
