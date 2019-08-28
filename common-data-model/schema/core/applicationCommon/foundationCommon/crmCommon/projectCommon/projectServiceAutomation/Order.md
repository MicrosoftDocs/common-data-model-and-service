---
title: Order - Common Data Model | Microsoft Docs
description: Quote that has been accepted.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Order

Quote that has been accepted.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/Order.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/Order  
- [/foundationCommon/crmCommon/sales/Order](../../sales/Order.md "/core/applicationCommon/foundationCommon/crmCommon/sales/Order.cdm.json/Order")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[salesOrderId](#salesOrderId)|Unique identifier of the order.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[emailAddress](#emailAddress)|The primary email address for the entity.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[name](#name)|Type a descriptive name for the order.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[billToAddressId](#billToAddressId)|Unique identifier of the billing address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[billToCity](#billToCity)|Type the city for the customer's billing address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[billToComposite](#billToComposite)|Shows the complete Bill To address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[billToContactName](#billToContactName)|Type the primary contact name at the customer's billing address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[billToCountry](#billToCountry)|Type the country or region for the customer's billing address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[billToFax](#billToFax)|Type the fax number for the customer's billing address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[billToLine1](#billToLine1)|Type the first line of the customer's billing address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[billToLine2](#billToLine2)|Type the second line of the customer's billing address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[billToLine3](#billToLine3)|Type the third line of the billing address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[billToName](#billToName)|Type a name for the customer's billing address, such as "Headquarters" or "Field office", to identify the address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[billToPostalCode](#billToPostalCode)|Type the ZIP Code or postal code for the billing address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[billToStateOrProvince](#billToStateOrProvince)|Type the state or province for the billing address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[billToTelephone](#billToTelephone)|Type the phone number for the customer's billing address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[customerIdType](#customerIdType)|The type of customer, either Account or Contact.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[customerId](#customerId)|The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[dateFulfilled](#dateFulfilled)|Enter the date that all or part of the order was shipped to the customer.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[description](#description)|Type additional information to describe the order, such as the products or services offered or details about the customer's product preferences.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[discountAmount](#discountAmount)|Type the discount amount for the order if the customer is eligible for special savings.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[discountAmountBase](#discountAmountBase)|Value of the Order Discount Amount in base currency.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[discountPercentage](#discountPercentage)|Type the discount rate that should be applied to the Detail Amount field to include additional savings for the customer in the order.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[freightAmount](#freightAmount)|Type the cost of freight or shipping for the products included in the order for use in calculating the Total Amount field.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[freightAmountBase](#freightAmountBase)|Value of the Freight Amount in base currency.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[freightTermsCode](#freightTermsCode)|Select the freight terms to make sure shipping charges are processed correctly.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[freightTermsCode_display](#freightTermsCode_display)||<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[isPriceLocked](#isPriceLocked)|Select whether prices specified on the invoice are locked from any further updates.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[lastBackofficeSubmit](#lastBackofficeSubmit)|Enter the date and time when the order was last submitted to an accounting or ERP system for processing.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[opportunityId](#opportunityId)|Choose the related opportunity so that the data for the order and opportunity are linked for reporting and analytics.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[orderNumber](#orderNumber)|Shows the order number for customer reference and to use in search. The number cannot be modified.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[paymentTermsCode](#paymentTermsCode)|Select the payment terms to indicate when the customer needs to pay the total amount.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[paymentTermsCode_display](#paymentTermsCode_display)||<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[priceLevelId](#priceLevelId)|Choose the price list associated with this record to make sure the products associated with the campaign are offered at the correct prices.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[pricingErrorCode](#pricingErrorCode)|Select the type of pricing error, such as a missing or invalid product, or missing quantity.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[pricingErrorCode_display](#pricingErrorCode_display)||<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[priorityCode](#priorityCode)|Select the priority so that preferred customers or critical issues are handled quickly.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[priorityCode_display](#priorityCode_display)||<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[quoteId](#quoteId)|Choose the related quote so that order data and quote data are linked for reporting and analytics.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[requestDeliveryBy](#requestDeliveryBy)|Enter the delivery date requested by the customer for all products in the order.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[shippingMethodCode](#shippingMethodCode)|Select a shipping method for deliveries sent to this address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[shippingMethodCode_display](#shippingMethodCode_display)||<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[shipToAddressId](#shipToAddressId)|Unique identifier of the shipping address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[shipToCity](#shipToCity)|Type the city for the customer's shipping address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[shipToComposite](#shipToComposite)|Shows the complete Ship To address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[shipToContactName](#shipToContactName)|Type the primary contact name at the customer's shipping address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[shipToCountry](#shipToCountry)|Type the country or region for the customer's shipping address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[shipToFax](#shipToFax)|Type the fax number for the customer's shipping address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[shipToFreightTermsCode](#shipToFreightTermsCode)|Select the freight terms to make sure shipping orders are processed correctly.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[shipToFreightTermsCode_display](#shipToFreightTermsCode_display)||<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[shipToLine1](#shipToLine1)|Type the first line of the customer's shipping address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[shipToLine2](#shipToLine2)|Type the second line of the customer's shipping address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[shipToLine3](#shipToLine3)|Type the third line of the shipping address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[shipToName](#shipToName)|Type a name for the customer's shipping address, such as "Headquarters" or "Field office",  to identify the address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[shipToPostalCode](#shipToPostalCode)|Type the ZIP Code or postal code for the shipping address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[shipToStateOrProvince](#shipToStateOrProvince)|Type the state or province for the shipping address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[shipToTelephone](#shipToTelephone)|Type the phone number for the customer's shipping address.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[stateCode](#stateCode)|Shows whether the order is active, submitted, fulfilled, canceled, or invoiced. Only active orders can be edited.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[stateCode_display](#stateCode_display)||<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[statusCode](#statusCode)|Select the order's status.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[statusCode_display](#statusCode_display)||<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[submitDate](#submitDate)|Enter the date when the order was submitted to the fulfillment or shipping center.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[submitStatus](#submitStatus)|Type the code for the submitted status in the fulfillment or shipping center system.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[submitStatusDescription](#submitStatusDescription)|Type additional details or notes about the order for the fulfillment or shipping center.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[totalAmount](#totalAmount)|Shows the total amount due, calculated as the sum of the products, discounts, freight, and taxes for the order.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[totalAmountBase](#totalAmountBase)|Value of the Total Amount in base currency.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[totalAmountLessFreight](#totalAmountLessFreight)|Shows the total product amount for the order, minus any discounts. This value is added to freight and tax amounts in the calculation for the total amount due for the order.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[totalAmountLessFreightBase](#totalAmountLessFreightBase)|Value of the Total Pre-Freight Amount in base currency.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[totalDiscountAmount](#totalDiscountAmount)|Shows the total discount amount, based on the discount price and rate entered on the order.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[totalDiscountAmountBase](#totalDiscountAmountBase)|Value of the Total Discount Amount in base currency.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[totalLineItemAmount](#totalLineItemAmount)|Shows the sum of all existing and write-in products included on the order, based on the specified price list and quantities.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[totalLineItemAmountBase](#totalLineItemAmountBase)|Value of the Total Detail Amount in base currency.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[totalLineItemDiscountAmount](#totalLineItemDiscountAmount)|Shows the total of the Manual Discount amounts specified on all products included in the order. This value is reflected in the Detail Amount field on the order and is added to any discount amount or rate specified on the order.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[totalLineItemDiscountAmountBase](#totalLineItemDiscountAmountBase)|Value of the Total Line Item Discount Amount in base currency.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[totalTax](#totalTax)|Shows the Tax amounts specified on all products included in the order, included in the Total Amount due calculation for the order.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[totalTaxBase](#totalTaxBase)|Value of the Total Tax in base currency.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[willCall](#willCall)|Select whether the products included in the order should be shipped to the specified address or held until the customer calls with further pick-up or delivery instructions.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[onHoldTime](#onHoldTime)|Shows the duration in minutes for which the order was on hold.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[lastOnHoldTime](#lastOnHoldTime)|Contains the date time stamp of the last on hold time.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[SLAId](#SLAId)|Choose the service level agreement (SLA) that you want to apply to the sales order record.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[SLAInvokedId](#SLAInvokedId)|Last SLA that was applied to this sales order. This field is for internal use only.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[entityImageId](#entityImageId)||<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[accountId](#accountId)|Shows the parent account related to the record. This information is used to link the sales order to the account selected in the Customer field for reporting and analytics.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[contactId](#contactId)|Shows the parent contact related to the record. This information is used to link the contract to the contact selected in the Customer field for reporting and analytics.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[campaignId](#campaignId)|Shows the campaign that the order was created from.|<a href="../../sales/Order.md" target="_blank">sales/Order</a>|
|[accountManagerId](#accountManagerId)|User responsible for managing the account referenced by this contract.|<a href="Order.md" target="_blank">projectServiceAutomation/Order</a>|
|[contractOrganizationalUnitId](#contractOrganizationalUnitId)|Organizational unit responsible for this contract.|<a href="Order.md" target="_blank">projectServiceAutomation/Order</a>|
|[orderType](#orderType)|Whether it is for an Item- based or a Work-based sale|<a href="Order.md" target="_blank">projectServiceAutomation/Order</a>|
|[orderType_display](#orderType_display)||<a href="Order.md" target="_blank">projectServiceAutomation/Order</a>|
|[PSAState](#PSAState)|Shows the current state of the project contract.|<a href="Order.md" target="_blank">projectServiceAutomation/Order</a>|
|[PSAState_display](#PSAState_display)||<a href="Order.md" target="_blank">projectServiceAutomation/Order</a>|
|[PSAStatusReason](#PSAStatusReason)|Shows the reason for the project contract status.|<a href="Order.md" target="_blank">projectServiceAutomation/Order</a>|
|[PSAStatusReason_display](#PSAStatusReason_display)||<a href="Order.md" target="_blank">projectServiceAutomation/Order</a>|
|[totalChargeableCostRollup](#totalChargeableCostRollup)|Value of the estimated chargeable cost.|<a href="Order.md" target="_blank">projectServiceAutomation/Order</a>|
|[totalChargeableCostRollupBase](#totalChargeableCostRollupBase)|Value of the Total Chargeable Cost in base currency.|<a href="Order.md" target="_blank">projectServiceAutomation/Order</a>|
|[totalNonchargeableCostRollup](#totalNonchargeableCostRollup)|Total estimated cost that will not be charged to the customer.|<a href="Order.md" target="_blank">projectServiceAutomation/Order</a>|
|[totalNonchargeableCostRollupBase](#totalNonchargeableCostRollupBase)|Value of the Total Non-chargeable Cost in base currency.|<a href="Order.md" target="_blank">projectServiceAutomation/Order</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#salesOrderId name="salesOrderId">salesOrderId</a>

Unique identifier of the order.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Order</td></tr><tr><td>description</td><td>Unique identifier of the order.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>salesorderid</td></tr></table>

### <a href=#emailAddress name="emailAddress">emailAddress</a>

The primary email address for the entity.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Address</td></tr><tr><td>description</td><td>The primary email address for the entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress</td></tr></table>

### <a href=#name name="name">name</a>

Type a descriptive name for the order.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type a descriptive name for the order.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>300</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#billToAddressId name="billToAddressId">billToAddressId</a>

Unique identifier of the billing address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Address ID</td></tr><tr><td>description</td><td>Unique identifier of the billing address.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_addressid</td></tr></table>

### <a href=#billToCity name="billToCity">billToCity</a>

Type the city for the customer's billing address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To City</td></tr><tr><td>description</td><td>Type the city for the customer's billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_city</td></tr></table>

### <a href=#billToComposite name="billToComposite">billToComposite</a>

Shows the complete Bill To address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Address</td></tr><tr><td>description</td><td>Shows the complete Bill To address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_composite</td></tr></table>

### <a href=#billToContactName name="billToContactName">billToContactName</a>

Type the primary contact name at the customer's billing address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Contact Name</td></tr><tr><td>description</td><td>Type the primary contact name at the customer's billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_contactname</td></tr></table>

### <a href=#billToCountry name="billToCountry">billToCountry</a>

Type the country or region for the customer's billing address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Country/Region</td></tr><tr><td>description</td><td>Type the country or region for the customer's billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_country</td></tr></table>

### <a href=#billToFax name="billToFax">billToFax</a>

Type the fax number for the customer's billing address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Fax</td></tr><tr><td>description</td><td>Type the fax number for the customer's billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_fax</td></tr></table>

### <a href=#billToLine1 name="billToLine1">billToLine1</a>

Type the first line of the customer's billing address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Street 1</td></tr><tr><td>description</td><td>Type the first line of the customer's billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_line1</td></tr></table>

### <a href=#billToLine2 name="billToLine2">billToLine2</a>

Type the second line of the customer's billing address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Street 2</td></tr><tr><td>description</td><td>Type the second line of the customer's billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_line2</td></tr></table>

### <a href=#billToLine3 name="billToLine3">billToLine3</a>

Type the third line of the billing address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Street 3</td></tr><tr><td>description</td><td>Type the third line of the billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_line3</td></tr></table>

### <a href=#billToName name="billToName">billToName</a>

Type a name for the customer's billing address, such as "Headquarters" or "Field office", to identify the address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Name</td></tr><tr><td>description</td><td>Type a name for the customer's billing address, such as "Headquarters" or "Field office", to identify the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_name</td></tr></table>

### <a href=#billToPostalCode name="billToPostalCode">billToPostalCode</a>

Type the ZIP Code or postal code for the billing address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To ZIP/Postal Code</td></tr><tr><td>description</td><td>Type the ZIP Code or postal code for the billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_postalcode</td></tr></table>

### <a href=#billToStateOrProvince name="billToStateOrProvince">billToStateOrProvince</a>

Type the state or province for the billing address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To State/Province</td></tr><tr><td>description</td><td>Type the state or province for the billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_stateorprovince</td></tr></table>

### <a href=#billToTelephone name="billToTelephone">billToTelephone</a>

Type the phone number for the customer's billing address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Phone</td></tr><tr><td>description</td><td>Type the phone number for the customer's billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_telephone</td></tr></table>

### <a href=#customerIdType name="customerIdType">customerIdType</a>

The type of customer, either Account or Contact.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>The type of customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>customeridtype</td></tr></table>

### <a href=#customerId name="customerId">customerId</a>

The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerid</td></tr></table>

### <a href=#dateFulfilled name="dateFulfilled">dateFulfilled</a>

Enter the date that all or part of the order was shipped to the customer.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Fulfilled</td></tr><tr><td>description</td><td>Enter the date that all or part of the order was shipped to the customer.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>datefulfilled</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the order, such as the products or services offered or details about the customer's product preferences.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the order, such as the products or services offered or details about the customer's product preferences.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#discountAmount name="discountAmount">discountAmount</a>

Type the discount amount for the order if the customer is eligible for special savings.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Order Discount Amount</td></tr><tr><td>description</td><td>Type the discount amount for the order if the customer is eligible for special savings.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>discountamount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#discountAmountBase name="discountAmountBase">discountAmountBase</a>

Value of the Order Discount Amount in base currency.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Order Discount Amount (Base)</td></tr><tr><td>description</td><td>Value of the Order Discount Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>discountamount_base</td></tr></table>

### <a href=#discountPercentage name="discountPercentage">discountPercentage</a>

Type the discount rate that should be applied to the Detail Amount field to include additional savings for the customer in the order.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Order Discount (%)</td></tr><tr><td>description</td><td>Type the discount rate that should be applied to the Detail Amount field to include additional savings for the customer in the order.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>discountpercentage</td></tr></table>

### <a href=#freightAmount name="freightAmount">freightAmount</a>

Type the cost of freight or shipping for the products included in the order for use in calculating the Total Amount field.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freight Amount</td></tr><tr><td>description</td><td>Type the cost of freight or shipping for the products included in the order for use in calculating the Total Amount field.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>freightamount</td></tr></table>

### <a href=#freightAmountBase name="freightAmountBase">freightAmountBase</a>

Value of the Freight Amount in base currency.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freight Amount (Base)</td></tr><tr><td>description</td><td>Value of the Freight Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>freightamount_base</td></tr></table>

### <a href=#freightTermsCode name="freightTermsCode">freightTermsCode</a>

Select the freight terms to make sure shipping charges are processed correctly.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freight Terms</td></tr><tr><td>description</td><td>Select the freight terms to make sure shipping charges are processed correctly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>freighttermscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>FOB</td><td>1</td></tr><tr><td>en</td><td>No Charge</td><td>2</td></tr></table></td></tr></table>

### <a href=#freightTermsCode_display name="freightTermsCode_display">freightTermsCode_display</a>

First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isPriceLocked name="isPriceLocked">isPriceLocked</a>

Select whether prices specified on the invoice are locked from any further updates.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Prices Locked</td></tr><tr><td>description</td><td>Select whether prices specified on the invoice are locked from any further updates.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ispricelocked</td></tr></table>

### <a href=#lastBackofficeSubmit name="lastBackofficeSubmit">lastBackofficeSubmit</a>

Enter the date and time when the order was last submitted to an accounting or ERP system for processing.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Submitted to Back Office</td></tr><tr><td>description</td><td>Enter the date and time when the order was last submitted to an accounting or ERP system for processing.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastbackofficesubmit</td></tr></table>

### <a href=#opportunityId name="opportunityId">opportunityId</a>

Choose the related opportunity so that the data for the order and opportunity are linked for reporting and analytics.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Opportunity</td></tr><tr><td>description</td><td>Choose the related opportunity so that the data for the order and opportunity are linked for reporting and analytics.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>opportunityid</td></tr></table>

### <a href=#orderNumber name="orderNumber">orderNumber</a>

Shows the order number for customer reference and to use in search. The number cannot be modified.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Order ID</td></tr><tr><td>description</td><td>Shows the order number for customer reference and to use in search. The number cannot be modified.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>ordernumber</td></tr></table>

### <a href=#paymentTermsCode name="paymentTermsCode">paymentTermsCode</a>

Select the payment terms to indicate when the customer needs to pay the total amount.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment Terms</td></tr><tr><td>description</td><td>Select the payment terms to indicate when the customer needs to pay the total amount.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>paymenttermscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Net 30</td><td>1</td></tr><tr><td>en</td><td>2% 10, Net 30</td><td>2</td></tr><tr><td>en</td><td>Net 45</td><td>3</td></tr><tr><td>en</td><td>Net 60</td><td>4</td></tr></table></td></tr></table>

### <a href=#paymentTermsCode_display name="paymentTermsCode_display">paymentTermsCode_display</a>

First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#priceLevelId name="priceLevelId">priceLevelId</a>

Choose the price list associated with this record to make sure the products associated with the campaign are offered at the correct prices.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price List</td></tr><tr><td>description</td><td>Choose the price list associated with this record to make sure the products associated with the campaign are offered at the correct prices.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>pricelevelid</td></tr></table>

### <a href=#pricingErrorCode name="pricingErrorCode">pricingErrorCode</a>

Select the type of pricing error, such as a missing or invalid product, or missing quantity.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pricing Error </td></tr><tr><td>description</td><td>Select the type of pricing error, such as a missing or invalid product, or missing quantity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>pricingerrorcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>0</td></tr><tr><td>en</td><td>Detail Error</td><td>1</td></tr><tr><td>en</td><td>Missing Price Level</td><td>2</td></tr><tr><td>en</td><td>Inactive Price Level</td><td>3</td></tr><tr><td>en</td><td>Missing Quantity</td><td>4</td></tr><tr><td>en</td><td>Missing Unit Price</td><td>5</td></tr><tr><td>en</td><td>Missing Product</td><td>6</td></tr><tr><td>en</td><td>Invalid Product</td><td>7</td></tr><tr><td>en</td><td>Missing Pricing Code</td><td>8</td></tr><tr><td>en</td><td>Invalid Pricing Code</td><td>9</td></tr><tr><td>en</td><td>Missing UOM</td><td>10</td></tr><tr><td>en</td><td>Product Not In Price Level</td><td>11</td></tr><tr><td>en</td><td>Missing Price Level Amount</td><td>12</td></tr><tr><td>en</td><td>Missing Price Level Percentage</td><td>13</td></tr><tr><td>en</td><td>Missing Price</td><td>14</td></tr><tr><td>en</td><td>Missing Current Cost</td><td>15</td></tr><tr><td>en</td><td>Missing Standard Cost</td><td>16</td></tr><tr><td>en</td><td>Invalid Price Level Amount</td><td>17</td></tr><tr><td>en</td><td>Invalid Price Level Percentage</td><td>18</td></tr><tr><td>en</td><td>Invalid Price</td><td>19</td></tr><tr><td>en</td><td>Invalid Current Cost</td><td>20</td></tr><tr><td>en</td><td>Invalid Standard Cost</td><td>21</td></tr><tr><td>en</td><td>Invalid Rounding Policy</td><td>22</td></tr><tr><td>en</td><td>Invalid Rounding Option</td><td>23</td></tr><tr><td>en</td><td>Invalid Rounding Amount</td><td>24</td></tr><tr><td>en</td><td>Price Calculation Error</td><td>25</td></tr><tr><td>en</td><td>Invalid Discount Type</td><td>26</td></tr><tr><td>en</td><td>Discount Type Invalid State</td><td>27</td></tr><tr><td>en</td><td>Invalid Discount</td><td>28</td></tr><tr><td>en</td><td>Invalid Quantity</td><td>29</td></tr><tr><td>en</td><td>Invalid Pricing Precision</td><td>30</td></tr><tr><td>en</td><td>Missing Product Default UOM</td><td>31</td></tr><tr><td>en</td><td>Missing Product UOM Schedule </td><td>32</td></tr><tr><td>en</td><td>Inactive Discount Type</td><td>33</td></tr><tr><td>en</td><td>Invalid Price Level Currency</td><td>34</td></tr><tr><td>en</td><td>Price Attribute Out Of Range</td><td>35</td></tr><tr><td>en</td><td>Base Currency Attribute Overflow</td><td>36</td></tr><tr><td>en</td><td>Base Currency Attribute Underflow</td><td>37</td></tr></table></td></tr></table>

### <a href=#pricingErrorCode_display name="pricingErrorCode_display">pricingErrorCode_display</a>

First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#priorityCode name="priorityCode">priorityCode</a>

Select the priority so that preferred customers or critical issues are handled quickly.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Select the priority so that preferred customers or critical issues are handled quickly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>prioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#priorityCode_display name="priorityCode_display">priorityCode_display</a>

First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#quoteId name="quoteId">quoteId</a>

Choose the related quote so that order data and quote data are linked for reporting and analytics.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote</td></tr><tr><td>description</td><td>Choose the related quote so that order data and quote data are linked for reporting and analytics.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>quoteid</td></tr></table>

### <a href=#requestDeliveryBy name="requestDeliveryBy">requestDeliveryBy</a>

Enter the delivery date requested by the customer for all products in the order.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requested Delivery Date</td></tr><tr><td>description</td><td>Enter the delivery date requested by the customer for all products in the order.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>requestdeliveryby</td></tr></table>

### <a href=#shippingMethodCode name="shippingMethodCode">shippingMethodCode</a>

Select a shipping method for deliveries sent to this address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping Method</td></tr><tr><td>description</td><td>Select a shipping method for deliveries sent to this address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Airborne</td><td>1</td></tr><tr><td>en</td><td>DHL</td><td>2</td></tr><tr><td>en</td><td>FedEx</td><td>3</td></tr><tr><td>en</td><td>UPS</td><td>4</td></tr><tr><td>en</td><td>Postal Mail</td><td>5</td></tr><tr><td>en</td><td>Full Load</td><td>6</td></tr><tr><td>en</td><td>Will Call</td><td>7</td></tr></table></td></tr></table>

### <a href=#shippingMethodCode_display name="shippingMethodCode_display">shippingMethodCode_display</a>

First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#shipToAddressId name="shipToAddressId">shipToAddressId</a>

Unique identifier of the shipping address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Address ID</td></tr><tr><td>description</td><td>Unique identifier of the shipping address.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_addressid</td></tr></table>

### <a href=#shipToCity name="shipToCity">shipToCity</a>

Type the city for the customer's shipping address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To City</td></tr><tr><td>description</td><td>Type the city for the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_city</td></tr></table>

### <a href=#shipToComposite name="shipToComposite">shipToComposite</a>

Shows the complete Ship To address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Address</td></tr><tr><td>description</td><td>Shows the complete Ship To address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_composite</td></tr></table>

### <a href=#shipToContactName name="shipToContactName">shipToContactName</a>

Type the primary contact name at the customer's shipping address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Contact Name</td></tr><tr><td>description</td><td>Type the primary contact name at the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_contactname</td></tr></table>

### <a href=#shipToCountry name="shipToCountry">shipToCountry</a>

Type the country or region for the customer's shipping address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Country/Region</td></tr><tr><td>description</td><td>Type the country or region for the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_country</td></tr></table>

### <a href=#shipToFax name="shipToFax">shipToFax</a>

Type the fax number for the customer's shipping address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship to Fax</td></tr><tr><td>description</td><td>Type the fax number for the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_fax</td></tr></table>

### <a href=#shipToFreightTermsCode name="shipToFreightTermsCode">shipToFreightTermsCode</a>

Select the freight terms to make sure shipping orders are processed correctly.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Freight Terms</td></tr><tr><td>description</td><td>Select the freight terms to make sure shipping orders are processed correctly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_freighttermscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#shipToFreightTermsCode_display name="shipToFreightTermsCode_display">shipToFreightTermsCode_display</a>

First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#shipToLine1 name="shipToLine1">shipToLine1</a>

Type the first line of the customer's shipping address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Street 1</td></tr><tr><td>description</td><td>Type the first line of the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_line1</td></tr></table>

### <a href=#shipToLine2 name="shipToLine2">shipToLine2</a>

Type the second line of the customer's shipping address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Street 2</td></tr><tr><td>description</td><td>Type the second line of the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_line2</td></tr></table>

### <a href=#shipToLine3 name="shipToLine3">shipToLine3</a>

Type the third line of the shipping address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Street 3</td></tr><tr><td>description</td><td>Type the third line of the shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_line3</td></tr></table>

### <a href=#shipToName name="shipToName">shipToName</a>

Type a name for the customer's shipping address, such as "Headquarters" or "Field office",  to identify the address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Name</td></tr><tr><td>description</td><td>Type a name for the customer's shipping address, such as "Headquarters" or "Field office",  to identify the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_name</td></tr></table>

### <a href=#shipToPostalCode name="shipToPostalCode">shipToPostalCode</a>

Type the ZIP Code or postal code for the shipping address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To ZIP/Postal Code</td></tr><tr><td>description</td><td>Type the ZIP Code or postal code for the shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_postalcode</td></tr></table>

### <a href=#shipToStateOrProvince name="shipToStateOrProvince">shipToStateOrProvince</a>

Type the state or province for the shipping address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To State/Province</td></tr><tr><td>description</td><td>Type the state or province for the shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_stateorprovince</td></tr></table>

### <a href=#shipToTelephone name="shipToTelephone">shipToTelephone</a>

Type the phone number for the customer's shipping address.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Phone</td></tr><tr><td>description</td><td>Type the phone number for the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_telephone</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the order is active, submitted, fulfilled, canceled, or invoiced. Only active orders can be edited.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the order is active, submitted, fulfilled, canceled, or invoiced. Only active orders can be edited.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Submitted</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>2</td></tr><tr><td>en</td><td>Fulfilled</td><td>3</td></tr><tr><td>en</td><td>Invoiced</td><td>4</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the order's status.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the order's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>In Progress</td><td>3</td><td>1</td></tr><tr><td>en</td><td>No Money</td><td>4</td><td>2</td></tr><tr><td>en</td><td>New</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Pending</td><td>2</td><td>0</td></tr><tr><td>en</td><td>Complete</td><td>100001</td><td>3</td></tr><tr><td>en</td><td>Partial</td><td>100002</td><td>3</td></tr><tr><td>en</td><td>Invoiced</td><td>100003</td><td>4</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#submitDate name="submitDate">submitDate</a>

Enter the date when the order was submitted to the fulfillment or shipping center.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Submitted</td></tr><tr><td>description</td><td>Enter the date when the order was submitted to the fulfillment or shipping center.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>submitdate</td></tr></table>

### <a href=#submitStatus name="submitStatus">submitStatus</a>

Type the code for the submitted status in the fulfillment or shipping center system.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Submitted Status</td></tr><tr><td>description</td><td>Type the code for the submitted status in the fulfillment or shipping center system.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>submitstatus</td></tr></table>

### <a href=#submitStatusDescription name="submitStatusDescription">submitStatusDescription</a>

Type additional details or notes about the order for the fulfillment or shipping center.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Submitted Status Description</td></tr><tr><td>description</td><td>Type additional details or notes about the order for the fulfillment or shipping center.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>submitstatusdescription</td></tr></table>

### <a href=#totalAmount name="totalAmount">totalAmount</a>

Shows the total amount due, calculated as the sum of the products, discounts, freight, and taxes for the order.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Amount</td></tr><tr><td>description</td><td>Shows the total amount due, calculated as the sum of the products, discounts, freight, and taxes for the order.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalamount</td></tr></table>

### <a href=#totalAmountBase name="totalAmountBase">totalAmountBase</a>

Value of the Total Amount in base currency.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Amount (Base)</td></tr><tr><td>description</td><td>Value of the Total Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalamount_base</td></tr></table>

### <a href=#totalAmountLessFreight name="totalAmountLessFreight">totalAmountLessFreight</a>

Shows the total product amount for the order, minus any discounts. This value is added to freight and tax amounts in the calculation for the total amount due for the order.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Pre-Freight Amount</td></tr><tr><td>description</td><td>Shows the total product amount for the order, minus any discounts. This value is added to freight and tax amounts in the calculation for the total amount due for the order.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalamountlessfreight</td></tr></table>

### <a href=#totalAmountLessFreightBase name="totalAmountLessFreightBase">totalAmountLessFreightBase</a>

Value of the Total Pre-Freight Amount in base currency.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Pre-Freight Amount (Base)</td></tr><tr><td>description</td><td>Value of the Total Pre-Freight Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalamountlessfreight_base</td></tr></table>

### <a href=#totalDiscountAmount name="totalDiscountAmount">totalDiscountAmount</a>

Shows the total discount amount, based on the discount price and rate entered on the order.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Discount Amount</td></tr><tr><td>description</td><td>Shows the total discount amount, based on the discount price and rate entered on the order.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totaldiscountamount</td></tr></table>

### <a href=#totalDiscountAmountBase name="totalDiscountAmountBase">totalDiscountAmountBase</a>

Value of the Total Discount Amount in base currency.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Discount Amount (Base)</td></tr><tr><td>description</td><td>Value of the Total Discount Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totaldiscountamount_base</td></tr></table>

### <a href=#totalLineItemAmount name="totalLineItemAmount">totalLineItemAmount</a>

Shows the sum of all existing and write-in products included on the order, based on the specified price list and quantities.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Detail Amount</td></tr><tr><td>description</td><td>Shows the sum of all existing and write-in products included on the order, based on the specified price list and quantities.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totallineitemamount</td></tr></table>

### <a href=#totalLineItemAmountBase name="totalLineItemAmountBase">totalLineItemAmountBase</a>

Value of the Total Detail Amount in base currency.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Detail Amount (Base)</td></tr><tr><td>description</td><td>Value of the Total Detail Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totallineitemamount_base</td></tr></table>

### <a href=#totalLineItemDiscountAmount name="totalLineItemDiscountAmount">totalLineItemDiscountAmount</a>

Shows the total of the Manual Discount amounts specified on all products included in the order. This value is reflected in the Detail Amount field on the order and is added to any discount amount or rate specified on the order.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Line Item Discount Amount</td></tr><tr><td>description</td><td>Shows the total of the Manual Discount amounts specified on all products included in the order. This value is reflected in the Detail Amount field on the order and is added to any discount amount or rate specified on the order.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totallineitemdiscountamount</td></tr></table>

### <a href=#totalLineItemDiscountAmountBase name="totalLineItemDiscountAmountBase">totalLineItemDiscountAmountBase</a>

Value of the Total Line Item Discount Amount in base currency.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Line Item Discount Amount (Base)</td></tr><tr><td>description</td><td>Value of the Total Line Item Discount Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totallineitemdiscountamount_base</td></tr></table>

### <a href=#totalTax name="totalTax">totalTax</a>

Shows the Tax amounts specified on all products included in the order, included in the Total Amount due calculation for the order.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Tax</td></tr><tr><td>description</td><td>Shows the Tax amounts specified on all products included in the order, included in the Total Amount due calculation for the order.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totaltax</td></tr></table>

### <a href=#totalTaxBase name="totalTaxBase">totalTaxBase</a>

Value of the Total Tax in base currency.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Tax (Base)</td></tr><tr><td>description</td><td>Value of the Total Tax in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totaltax_base</td></tr></table>

### <a href=#willCall name="willCall">willCall</a>

Select whether the products included in the order should be shipped to the specified address or held until the customer calls with further pick-up or delivery instructions.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To</td></tr><tr><td>description</td><td>Select whether the products included in the order should be shipped to the specified address or held until the customer calls with further pick-up or delivery instructions.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>willcall</td></tr></table>

### <a href=#onHoldTime name="onHoldTime">onHoldTime</a>

Shows the duration in minutes for which the order was on hold.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Hold Time (Minutes)</td></tr><tr><td>description</td><td>Shows the duration in minutes for which the order was on hold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>onholdtime</td></tr></table>

### <a href=#lastOnHoldTime name="lastOnHoldTime">lastOnHoldTime</a>

Contains the date time stamp of the last on hold time.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last On Hold Time</td></tr><tr><td>description</td><td>Contains the date time stamp of the last on hold time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastonholdtime</td></tr></table>

### <a href=#SLAId name="SLAId">SLAId</a>

Choose the service level agreement (SLA) that you want to apply to the sales order record.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Choose the service level agreement (SLA) that you want to apply to the sales order record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#SLAInvokedId name="SLAInvokedId">SLAInvokedId</a>

Last SLA that was applied to this sales order. This field is for internal use only.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last SLA applied</td></tr><tr><td>description</td><td>Last SLA that was applied to this sales order. This field is for internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slainvokedid</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Shows the parent account related to the record. This information is used to link the sales order to the account selected in the Customer field for reporting and analytics.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Shows the parent account related to the record. This information is used to link the sales order to the account selected in the Customer field for reporting and analytics.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>accountid</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Shows the parent contact related to the record. This information is used to link the contract to the contact selected in the Customer field for reporting and analytics.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Shows the parent contact related to the record. This information is used to link the contract to the contact selected in the Customer field for reporting and analytics.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>contactid</td></tr></table>

### <a href=#campaignId name="campaignId">campaignId</a>

Shows the campaign that the order was created from.  
First included in: <a href="../../sales/Order.md" target="_blank">sales/Order</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source Campaign</td></tr><tr><td>description</td><td>Shows the campaign that the order was created from.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>campaignid</td></tr></table>

### <a href=#accountManagerId name="accountManagerId">accountManagerId</a>

User responsible for managing the account referenced by this contract.  
First included in: projectServiceAutomation/Order (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account Manager</td></tr><tr><td>description</td><td>User responsible for managing the account referenced by this contract.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_accountmanagerid</td></tr></table>

### <a href=#contractOrganizationalUnitId name="contractOrganizationalUnitId">contractOrganizationalUnitId</a>

Organizational unit responsible for this contract.  
First included in: projectServiceAutomation/Order (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contracting Unit</td></tr><tr><td>description</td><td>Organizational unit responsible for this contract.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contractorganizationalunitid</td></tr></table>

### <a href=#orderType name="orderType">orderType</a>

Whether it is for an Item- based or a Work-based sale  
First included in: projectServiceAutomation/Order (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Order Type</td></tr><tr><td>description</td><td>Whether it is for an Item- based or a Work-based sale</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_ordertype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Item based</td><td>192350000</td></tr><tr><td>en</td><td>Work based</td><td>192350001</td></tr></table></td></tr></table>

### <a href=#orderType_display name="orderType_display">orderType_display</a>

First included in: projectServiceAutomation/Order (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#PSAState name="PSAState">PSAState</a>

Shows the current state of the project contract.  
First included in: projectServiceAutomation/Order (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract Status</td></tr><tr><td>description</td><td>Shows the current state of the project contract.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_psastate</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Draft</td><td>192350000</td></tr><tr><td>en</td><td>On hold</td><td>192350001</td></tr><tr><td>en</td><td>Active</td><td>192350002</td></tr><tr><td>en</td><td>Closed</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#PSAState_display name="PSAState_display">PSAState_display</a>

First included in: projectServiceAutomation/Order (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#PSAStatusReason name="PSAStatusReason">PSAStatusReason</a>

Shows the reason for the project contract status.  
First included in: projectServiceAutomation/Order (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract Status Reason</td></tr><tr><td>description</td><td>Shows the reason for the project contract status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_psastatusreason</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Draft</td><td>192350000</td></tr><tr><td>en</td><td>In review</td><td>192350001</td></tr><tr><td>en</td><td>On hold</td><td>192350002</td></tr><tr><td>en</td><td>Confirmed</td><td>192350003</td></tr><tr><td>en</td><td>Completed</td><td>192350004</td></tr><tr><td>en</td><td>Lost</td><td>192350005</td></tr><tr><td>en</td><td>Abandoned</td><td>192350006</td></tr></table></td></tr></table>

### <a href=#PSAStatusReason_display name="PSAStatusReason_display">PSAStatusReason_display</a>

First included in: projectServiceAutomation/Order (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#totalChargeableCostRollup name="totalChargeableCostRollup">totalChargeableCostRollup</a>

Value of the estimated chargeable cost.  
First included in: projectServiceAutomation/Order (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Chargeable Cost</td></tr><tr><td>description</td><td>Value of the estimated chargeable cost.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_totalchargeablecostrollup</td></tr></table>

### <a href=#totalChargeableCostRollupBase name="totalChargeableCostRollupBase">totalChargeableCostRollupBase</a>

Value of the Total Chargeable Cost in base currency.  
First included in: projectServiceAutomation/Order (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Chargeable Cost (Base)</td></tr><tr><td>description</td><td>Value of the Total Chargeable Cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_totalchargeablecostrollup_base</td></tr></table>

### <a href=#totalNonchargeableCostRollup name="totalNonchargeableCostRollup">totalNonchargeableCostRollup</a>

Total estimated cost that will not be charged to the customer.  
First included in: projectServiceAutomation/Order (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Non-chargeable Cost</td></tr><tr><td>description</td><td>Total estimated cost that will not be charged to the customer.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_totalnonchargeablecostrollup</td></tr></table>

### <a href=#totalNonchargeableCostRollupBase name="totalNonchargeableCostRollupBase">totalNonchargeableCostRollupBase</a>

Value of the Total Non-chargeable Cost in base currency.  
First included in: projectServiceAutomation/Order (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Non-chargeable Cost (Base)</td></tr><tr><td>description</td><td>Value of the Total Non-chargeable Cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_totalnonchargeablecostrollup_base</td></tr></table>
