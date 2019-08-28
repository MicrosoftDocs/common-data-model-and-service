---
title: Quote - Common Data Model | Microsoft Docs
description: This describes the Quote entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Quote

Formal offer for products and/or services, proposed at specific prices and related payment terms, which is sent to a prospective customer.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/Quote.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/projectCommon/projectServiceAutomation/Quote  
- [/foundationCommon/crmCommon/sales/Quote](../../sales/Quote.md "/core/applicationCommon/foundationCommon/crmCommon/sales/Quote.cdm.json/Quote")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[quoteId](#quoteId)|Unique identifier of the quote.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[emailAddress](#emailAddress)|The primary email address for the entity.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[name](#name)|Type a descriptive name for the quote.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[billToAddressId](#billToAddressId)|Unique identifier of the billing address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[billToCity](#billToCity)|Type the city for the customer's billing address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[billToComposite](#billToComposite)|Shows the complete Bill To address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[billToContactName](#billToContactName)|Type the primary contact name at the customer's billing address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[billToCountry](#billToCountry)|Type the country or region for the customer's billing address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[billToFax](#billToFax)|Type the fax number for the customer's billing address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[billToLine1](#billToLine1)|Type the first line of the customer's billing address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[billToLine2](#billToLine2)|Type the second line of the customer's billing address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[billToLine3](#billToLine3)|Type the third line of the billing address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[billToName](#billToName)|Type a name for the customer's billing address, such as "Headquarters" or "Field office", to identify the address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[billToPostalCode](#billToPostalCode)|Type the ZIP Code or postal code for the billing address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[billToStateOrProvince](#billToStateOrProvince)|Type the state or province for the billing address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[billToTelephone](#billToTelephone)|Type the phone number for the customer's billing address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[closedOn](#closedOn)|Enter the date when the quote was closed to indicate the expiration, revision, or cancellation date.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[customerIdType](#customerIdType)|The type of customer, either Account or Contact.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[customerId](#customerId)|The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[description](#description)|Type additional information to describe the quote, such as the products or services offered or details about the customer's product preferences.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[discountAmount](#discountAmount)|Type the discount amount for the quote if the customer is eligible for special savings.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[discountAmountBase](#discountAmountBase)|Value of the Quote Discount Amount in base currency.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[discountPercentage](#discountPercentage)|Type the discount rate that should be applied to the Detail Amount field to include additional savings for the customer in the quote.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[effectiveFrom](#effectiveFrom)|Enter the date when the quote pricing is effective or was first communicated to the customer.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[effectiveTo](#effectiveTo)|Enter the expiration date or last day the quote pricing is effective for the customer.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[expiresOn](#expiresOn)|Enter the date a decision or order is due from the customer to indicate the expiration date of the quote.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[freightAmount](#freightAmount)|Type the cost of freight or shipping for the products included in the quote for use in calculating the Total Amount field.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[freightAmountBase](#freightAmountBase)|Value of the Freight Amount in base currency.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[freightTermsCode](#freightTermsCode)|Select the freight terms to make sure shipping charges are processed correctly.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[freightTermsCode_display](#freightTermsCode_display)||<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[opportunityId](#opportunityId)|Choose the opportunity that the quote is related to for reporting and analytics.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[paymentTermsCode](#paymentTermsCode)|Select the payment terms to indicate when the customer needs to pay the total amount.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[paymentTermsCode_display](#paymentTermsCode_display)||<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[priceLevelId](#priceLevelId)|Choose the price list associated with this record to make sure the products associated with the campaign are offered at the correct prices.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[pricingErrorCode](#pricingErrorCode)|Pricing error for the quote.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[pricingErrorCode_display](#pricingErrorCode_display)||<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[quoteNumber](#quoteNumber)|Shows the quote number for customer reference and searching capabilities. The number cannot be modified.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[requestDeliveryBy](#requestDeliveryBy)|Enter the delivery date requested by the customer for all products in the quote.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[revisionNumber](#revisionNumber)|Shows the version number of the quote for revision history tracking.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[shippingMethodCode](#shippingMethodCode)|Select a shipping method for deliveries sent to this address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[shippingMethodCode_display](#shippingMethodCode_display)||<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[shipToAddressId](#shipToAddressId)|Unique identifier of the shipping address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[shipToCity](#shipToCity)|Type the city for the customer's shipping address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[shipToComposite](#shipToComposite)|Shows the complete Ship To address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[shipToContactName](#shipToContactName)|Type the primary contact name at the customer's shipping address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[shipToCountry](#shipToCountry)|Type the country or region for the customer's shipping address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[shipToFax](#shipToFax)|Type the fax number for the customer's shipping address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[shipToFreightTermsCode](#shipToFreightTermsCode)|Select the freight terms to make sure shipping orders are processed correctly.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[shipToFreightTermsCode_display](#shipToFreightTermsCode_display)||<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[shipToLine1](#shipToLine1)|Type the first line of the customer's shipping address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[shipToLine2](#shipToLine2)|Type the second line of the customer's shipping address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[shipToLine3](#shipToLine3)|Type the third line of the shipping address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[shipToName](#shipToName)|Type a name for the customer's shipping address, such as "Headquarters" or "Field office",  to identify the address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[shipToPostalCode](#shipToPostalCode)|Type the ZIP Code or postal code for the shipping address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[shipToStateOrProvince](#shipToStateOrProvince)|Type the state or province for the shipping address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[shipToTelephone](#shipToTelephone)|Type the phone number for the customer's shipping address.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[stateCode](#stateCode)|Shows whether the quote is draft, active, won, or closed. Only draft quotes can be edited.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[stateCode_display](#stateCode_display)||<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[statusCode](#statusCode)|Select the quote's status.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[statusCode_display](#statusCode_display)||<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[totalAmount](#totalAmount)|Shows the total amount due, calculated as the sum of the products, discounts, freight, and taxes for the quote.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[totalAmountBase](#totalAmountBase)|Value of the Total Amount in base currency.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[totalAmountLessFreight](#totalAmountLessFreight)|Shows the total product amount for the quote, minus any discounts. This value is added to freight and tax amounts in the calculation for the total amount due for the quote.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[totalAmountLessFreightBase](#totalAmountLessFreightBase)|Value of the Total Pre-Freight Amount in base currency.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[totalDiscountAmount](#totalDiscountAmount)|Shows the total discount amount, based on the discount price and rate entered on the quote.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[totalDiscountAmountBase](#totalDiscountAmountBase)|Value of the Total Discount Amount in base currency.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[totalLineItemAmount](#totalLineItemAmount)|Shows the sum of all existing and write-in products included on the quote, based on the specified price list and quantities.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[totalLineItemAmountBase](#totalLineItemAmountBase)|Value of the Total Detail Amount in base currency.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[totalLineItemDiscountAmount](#totalLineItemDiscountAmount)|Shows the total of the Manual Discount amounts specified on all products included in the quote. This value is reflected in the Detail Amount field on the quote and is added to any discount amount or rate specified on the quote|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[totalLineItemDiscountAmountBase](#totalLineItemDiscountAmountBase)|Value of the Total Line Item Discount Amount in base currency.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[totalTax](#totalTax)|Shows the total of the Tax amounts specified on all products included in the quote, included in the Total Amount due calculation for the quote.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[totalTaxBase](#totalTaxBase)|Value of the Total Tax in base currency.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[willCall](#willCall)|Select whether the products included in the quote should be shipped to the specified address or held until the customer calls with further pick up or delivery instructions.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[onHoldTime](#onHoldTime)|Shows the duration in minutes for which the quote was on hold.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[lastOnHoldTime](#lastOnHoldTime)|Contains the date time stamp of the last on hold time.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[SLAId](#SLAId)|Choose the service level agreement (SLA) that you want to apply to the quote record.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[SLAInvokedId](#SLAInvokedId)|Last SLA that was applied to this quote. This field is for internal use only.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[accountId](#accountId)|Unique identifier of the account with which the quote is associated.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[contactId](#contactId)|Unique identifier of the contact associated with the quote.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[campaignId](#campaignId)|Shows the campaign that the order was created from.|<a href="../../sales/Quote.md" target="_blank">sales/Quote</a>|
|[accountManagerId](#accountManagerId)|Account manager responsible for the quote.|<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[contractOrganizationalUnitId](#contractOrganizationalUnitId)|The organizational unit in charge of the contract.|<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[feasible](#feasible)|Shows how the quote estimation compares to project estimation. Possible values are 0: Feasibility Not Available, 1: Feasible, and 2: Not Feasible.|<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[feasible_display](#feasible_display)||<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[orderType](#orderType)|Select whether the project contract is for an item-based or a work-based sale.|<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[orderType_display](#orderType_display)||<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[adjustedGrossMargin](#adjustedGrossMargin)|Shows the estimated gross margin after accounting for non-chargeable components.|<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[competitive](#competitive)|Shows how the quote estimation of sales value and schedule compare to customer expectations on those parameters. Possible values are 1: Within Customer expectations, 2: Not Within Customer expectations, and 0: Customer expectations Not Available.|<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[competitive_display](#competitive_display)||<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[customerBudgetRollUp](#customerBudgetRollUp)|Shows the total customer budget for the quote, computed from all the quote lines.|<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[customerBudgetRollupBase](#customerBudgetRollupBase)|Shows the value of the customer budget in the base currency.|<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[estimatedBudget](#estimatedBudget)|Shows how the estimated sales value on the quote compares to customer budgets. Possible values are 1: Within Customer Budget, 2: Exceeds Customer Budget, 0: Budget Estimate Not Available|<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[estimatedBudget_display](#estimatedBudget_display)||<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[estimatedCompletionRollUp](#estimatedCompletionRollUp)|Estimated completion date, computed from the details of each quote line.|<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[estimatedSchedule](#estimatedSchedule)|Shows how the estimated schedule on the quote compares to customer expectations. Possible values are 1: Estimated To Finish Early, 2: Estimated To Finish Late, 3: Estimated To Finish On Schedule, and 0: Schedule Not Available.|<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[estimatedSchedule_display](#estimatedSchedule_display)||<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[grossMargin](#grossMargin)|Shows the estimated gross margin without accounting for non-chargeable components.|<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[profitability](#profitability)|Shows the estimated profitability of the quote. Possible values are Profitable, Not Profitable, and Profitability not available.|<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[profitability_display](#profitability_display)||<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[totalChargeableCostRollup](#totalChargeableCostRollup)||<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[totalChargeableCostRollupBase](#totalChargeableCostRollupBase)|Value of the Total Chargeable Cost in base currency.|<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[totalNonchargeableCostRollup](#totalNonchargeableCostRollup)||<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|
|[totalNonchargeableCostRollupBase](#totalNonchargeableCostRollupBase)|Value of the Total Non-chargeable Cost in base currency.|<a href="Quote.md" target="_blank">projectServiceAutomation/Quote</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#quoteId name="quoteId">quoteId</a>

Unique identifier of the quote.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote</td></tr><tr><td>description</td><td>Unique identifier of the quote.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>quoteid</td></tr></table>

### <a href=#emailAddress name="emailAddress">emailAddress</a>

The primary email address for the entity.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Address</td></tr><tr><td>description</td><td>The primary email address for the entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress</td></tr></table>

### <a href=#name name="name">name</a>

Type a descriptive name for the quote.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type a descriptive name for the quote.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>300</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#billToAddressId name="billToAddressId">billToAddressId</a>

Unique identifier of the billing address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Address ID</td></tr><tr><td>description</td><td>Unique identifier of the billing address.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_addressid</td></tr></table>

### <a href=#billToCity name="billToCity">billToCity</a>

Type the city for the customer's billing address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To City</td></tr><tr><td>description</td><td>Type the city for the customer's billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_city</td></tr></table>

### <a href=#billToComposite name="billToComposite">billToComposite</a>

Shows the complete Bill To address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Address</td></tr><tr><td>description</td><td>Shows the complete Bill To address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_composite</td></tr></table>

### <a href=#billToContactName name="billToContactName">billToContactName</a>

Type the primary contact name at the customer's billing address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Contact Name</td></tr><tr><td>description</td><td>Type the primary contact name at the customer's billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_contactname</td></tr></table>

### <a href=#billToCountry name="billToCountry">billToCountry</a>

Type the country or region for the customer's billing address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Country/Region</td></tr><tr><td>description</td><td>Type the country or region for the customer's billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_country</td></tr></table>

### <a href=#billToFax name="billToFax">billToFax</a>

Type the fax number for the customer's billing address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Fax</td></tr><tr><td>description</td><td>Type the fax number for the customer's billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_fax</td></tr></table>

### <a href=#billToLine1 name="billToLine1">billToLine1</a>

Type the first line of the customer's billing address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Street 1</td></tr><tr><td>description</td><td>Type the first line of the customer's billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_line1</td></tr></table>

### <a href=#billToLine2 name="billToLine2">billToLine2</a>

Type the second line of the customer's billing address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Street 2</td></tr><tr><td>description</td><td>Type the second line of the customer's billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_line2</td></tr></table>

### <a href=#billToLine3 name="billToLine3">billToLine3</a>

Type the third line of the billing address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Street 3</td></tr><tr><td>description</td><td>Type the third line of the billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_line3</td></tr></table>

### <a href=#billToName name="billToName">billToName</a>

Type a name for the customer's billing address, such as "Headquarters" or "Field office", to identify the address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Name</td></tr><tr><td>description</td><td>Type a name for the customer's billing address, such as "Headquarters" or "Field office", to identify the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_name</td></tr></table>

### <a href=#billToPostalCode name="billToPostalCode">billToPostalCode</a>

Type the ZIP Code or postal code for the billing address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To ZIP/Postal Code</td></tr><tr><td>description</td><td>Type the ZIP Code or postal code for the billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_postalcode</td></tr></table>

### <a href=#billToStateOrProvince name="billToStateOrProvince">billToStateOrProvince</a>

Type the state or province for the billing address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To State/Province</td></tr><tr><td>description</td><td>Type the state or province for the billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_stateorprovince</td></tr></table>

### <a href=#billToTelephone name="billToTelephone">billToTelephone</a>

Type the phone number for the customer's billing address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bill To Phone</td></tr><tr><td>description</td><td>Type the phone number for the customer's billing address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>billto_telephone</td></tr></table>

### <a href=#closedOn name="closedOn">closedOn</a>

Enter the date when the quote was closed to indicate the expiration, revision, or cancellation date.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Closed On</td></tr><tr><td>description</td><td>Enter the date when the quote was closed to indicate the expiration, revision, or cancellation date.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>closedon</td></tr></table>

### <a href=#customerIdType name="customerIdType">customerIdType</a>

The type of customer, either Account or Contact.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>The type of customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>customeridtype</td></tr></table>

### <a href=#customerId name="customerId">customerId</a>

The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerid</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the quote, such as the products or services offered or details about the customer's product preferences.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the quote, such as the products or services offered or details about the customer's product preferences.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#discountAmount name="discountAmount">discountAmount</a>

Type the discount amount for the quote if the customer is eligible for special savings.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote Discount Amount</td></tr><tr><td>description</td><td>Type the discount amount for the quote if the customer is eligible for special savings.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>discountamount</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#discountAmountBase name="discountAmountBase">discountAmountBase</a>

Value of the Quote Discount Amount in base currency.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote Discount Amount (Base)</td></tr><tr><td>description</td><td>Value of the Quote Discount Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>discountamount_base</td></tr></table>

### <a href=#discountPercentage name="discountPercentage">discountPercentage</a>

Type the discount rate that should be applied to the Detail Amount field to include additional savings for the customer in the quote.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote Discount (%)</td></tr><tr><td>description</td><td>Type the discount rate that should be applied to the Detail Amount field to include additional savings for the customer in the quote.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>discountpercentage</td></tr></table>

### <a href=#effectiveFrom name="effectiveFrom">effectiveFrom</a>

Enter the date when the quote pricing is effective or was first communicated to the customer.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effective From</td></tr><tr><td>description</td><td>Enter the date when the quote pricing is effective or was first communicated to the customer.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>effectivefrom</td></tr></table>

### <a href=#effectiveTo name="effectiveTo">effectiveTo</a>

Enter the expiration date or last day the quote pricing is effective for the customer.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effective To</td></tr><tr><td>description</td><td>Enter the expiration date or last day the quote pricing is effective for the customer.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>effectiveto</td></tr></table>

### <a href=#expiresOn name="expiresOn">expiresOn</a>

Enter the date a decision or order is due from the customer to indicate the expiration date of the quote.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Due By</td></tr><tr><td>description</td><td>Enter the date a decision or order is due from the customer to indicate the expiration date of the quote.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>expireson</td></tr></table>

### <a href=#freightAmount name="freightAmount">freightAmount</a>

Type the cost of freight or shipping for the products included in the quote for use in calculating the Total Amount field.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freight Amount</td></tr><tr><td>description</td><td>Type the cost of freight or shipping for the products included in the quote for use in calculating the Total Amount field.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>freightamount</td></tr></table>

### <a href=#freightAmountBase name="freightAmountBase">freightAmountBase</a>

Value of the Freight Amount in base currency.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freight Amount (Base)</td></tr><tr><td>description</td><td>Value of the Freight Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>freightamount_base</td></tr></table>

### <a href=#freightTermsCode name="freightTermsCode">freightTermsCode</a>

Select the freight terms to make sure shipping charges are processed correctly.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freight Terms</td></tr><tr><td>description</td><td>Select the freight terms to make sure shipping charges are processed correctly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>freighttermscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>FOB</td><td>1</td></tr><tr><td>en</td><td>No Charge</td><td>2</td></tr></table></td></tr></table>

### <a href=#freightTermsCode_display name="freightTermsCode_display">freightTermsCode_display</a>

First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#opportunityId name="opportunityId">opportunityId</a>

Choose the opportunity that the quote is related to for reporting and analytics.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Opportunity</td></tr><tr><td>description</td><td>Choose the opportunity that the quote is related to for reporting and analytics.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>opportunityid</td></tr></table>

### <a href=#paymentTermsCode name="paymentTermsCode">paymentTermsCode</a>

Select the payment terms to indicate when the customer needs to pay the total amount.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment Terms</td></tr><tr><td>description</td><td>Select the payment terms to indicate when the customer needs to pay the total amount.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>paymenttermscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Net 30</td><td>1</td></tr><tr><td>en</td><td>2% 10, Net 30</td><td>2</td></tr><tr><td>en</td><td>Net 45</td><td>3</td></tr><tr><td>en</td><td>Net 60</td><td>4</td></tr></table></td></tr></table>

### <a href=#paymentTermsCode_display name="paymentTermsCode_display">paymentTermsCode_display</a>

First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#priceLevelId name="priceLevelId">priceLevelId</a>

Choose the price list associated with this record to make sure the products associated with the campaign are offered at the correct prices.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price List</td></tr><tr><td>description</td><td>Choose the price list associated with this record to make sure the products associated with the campaign are offered at the correct prices.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>pricelevelid</td></tr></table>

### <a href=#pricingErrorCode name="pricingErrorCode">pricingErrorCode</a>

Pricing error for the quote.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pricing Error </td></tr><tr><td>description</td><td>Pricing error for the quote.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>pricingerrorcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>0</td></tr><tr><td>en</td><td>Detail Error</td><td>1</td></tr><tr><td>en</td><td>Missing Price Level</td><td>2</td></tr><tr><td>en</td><td>Inactive Price Level</td><td>3</td></tr><tr><td>en</td><td>Missing Quantity</td><td>4</td></tr><tr><td>en</td><td>Missing Unit Price</td><td>5</td></tr><tr><td>en</td><td>Missing Product</td><td>6</td></tr><tr><td>en</td><td>Invalid Product</td><td>7</td></tr><tr><td>en</td><td>Missing Pricing Code</td><td>8</td></tr><tr><td>en</td><td>Invalid Pricing Code</td><td>9</td></tr><tr><td>en</td><td>Missing UOM</td><td>10</td></tr><tr><td>en</td><td>Product Not In Price Level</td><td>11</td></tr><tr><td>en</td><td>Missing Price Level Amount</td><td>12</td></tr><tr><td>en</td><td>Missing Price Level Percentage</td><td>13</td></tr><tr><td>en</td><td>Missing Price</td><td>14</td></tr><tr><td>en</td><td>Missing Current Cost</td><td>15</td></tr><tr><td>en</td><td>Missing Standard Cost</td><td>16</td></tr><tr><td>en</td><td>Invalid Price Level Amount</td><td>17</td></tr><tr><td>en</td><td>Invalid Price Level Percentage</td><td>18</td></tr><tr><td>en</td><td>Invalid Price</td><td>19</td></tr><tr><td>en</td><td>Invalid Current Cost</td><td>20</td></tr><tr><td>en</td><td>Invalid Standard Cost</td><td>21</td></tr><tr><td>en</td><td>Invalid Rounding Policy</td><td>22</td></tr><tr><td>en</td><td>Invalid Rounding Option</td><td>23</td></tr><tr><td>en</td><td>Invalid Rounding Amount</td><td>24</td></tr><tr><td>en</td><td>Price Calculation Error</td><td>25</td></tr><tr><td>en</td><td>Invalid Discount Type</td><td>26</td></tr><tr><td>en</td><td>Discount Type Invalid State</td><td>27</td></tr><tr><td>en</td><td>Invalid Discount</td><td>28</td></tr><tr><td>en</td><td>Invalid Quantity</td><td>29</td></tr><tr><td>en</td><td>Invalid Pricing Precision</td><td>30</td></tr><tr><td>en</td><td>Missing Product Default UOM</td><td>31</td></tr><tr><td>en</td><td>Missing Product UOM Schedule </td><td>32</td></tr><tr><td>en</td><td>Inactive Discount Type</td><td>33</td></tr><tr><td>en</td><td>Invalid Price Level Currency</td><td>34</td></tr><tr><td>en</td><td>Price Attribute Out Of Range</td><td>35</td></tr><tr><td>en</td><td>Base Currency Attribute Overflow</td><td>36</td></tr><tr><td>en</td><td>Base Currency Attribute Underflow</td><td>37</td></tr></table></td></tr></table>

### <a href=#pricingErrorCode_display name="pricingErrorCode_display">pricingErrorCode_display</a>

First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#quoteNumber name="quoteNumber">quoteNumber</a>

Shows the quote number for customer reference and searching capabilities. The number cannot be modified.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote ID</td></tr><tr><td>description</td><td>Shows the quote number for customer reference and searching capabilities. The number cannot be modified.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>quotenumber</td></tr></table>

### <a href=#requestDeliveryBy name="requestDeliveryBy">requestDeliveryBy</a>

Enter the delivery date requested by the customer for all products in the quote.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requested Delivery Date</td></tr><tr><td>description</td><td>Enter the delivery date requested by the customer for all products in the quote.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>requestdeliveryby</td></tr></table>

### <a href=#revisionNumber name="revisionNumber">revisionNumber</a>

Shows the version number of the quote for revision history tracking.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Revision ID</td></tr><tr><td>description</td><td>Shows the version number of the quote for revision history tracking.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>revisionnumber</td></tr></table>

### <a href=#shippingMethodCode name="shippingMethodCode">shippingMethodCode</a>

Select a shipping method for deliveries sent to this address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping Method</td></tr><tr><td>description</td><td>Select a shipping method for deliveries sent to this address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Airborne</td><td>1</td></tr><tr><td>en</td><td>DHL</td><td>2</td></tr><tr><td>en</td><td>FedEx</td><td>3</td></tr><tr><td>en</td><td>UPS</td><td>4</td></tr><tr><td>en</td><td>Postal Mail</td><td>5</td></tr><tr><td>en</td><td>Full Load</td><td>6</td></tr><tr><td>en</td><td>Will Call</td><td>7</td></tr></table></td></tr></table>

### <a href=#shippingMethodCode_display name="shippingMethodCode_display">shippingMethodCode_display</a>

First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#shipToAddressId name="shipToAddressId">shipToAddressId</a>

Unique identifier of the shipping address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Address ID</td></tr><tr><td>description</td><td>Unique identifier of the shipping address.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_addressid</td></tr></table>

### <a href=#shipToCity name="shipToCity">shipToCity</a>

Type the city for the customer's shipping address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To City</td></tr><tr><td>description</td><td>Type the city for the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_city</td></tr></table>

### <a href=#shipToComposite name="shipToComposite">shipToComposite</a>

Shows the complete Ship To address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Address</td></tr><tr><td>description</td><td>Shows the complete Ship To address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_composite</td></tr></table>

### <a href=#shipToContactName name="shipToContactName">shipToContactName</a>

Type the primary contact name at the customer's shipping address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Contact Name</td></tr><tr><td>description</td><td>Type the primary contact name at the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>150</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_contactname</td></tr></table>

### <a href=#shipToCountry name="shipToCountry">shipToCountry</a>

Type the country or region for the customer's shipping address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Country/Region</td></tr><tr><td>description</td><td>Type the country or region for the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_country</td></tr></table>

### <a href=#shipToFax name="shipToFax">shipToFax</a>

Type the fax number for the customer's shipping address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Fax</td></tr><tr><td>description</td><td>Type the fax number for the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_fax</td></tr></table>

### <a href=#shipToFreightTermsCode name="shipToFreightTermsCode">shipToFreightTermsCode</a>

Select the freight terms to make sure shipping orders are processed correctly.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Freight Terms</td></tr><tr><td>description</td><td>Select the freight terms to make sure shipping orders are processed correctly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_freighttermscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#shipToFreightTermsCode_display name="shipToFreightTermsCode_display">shipToFreightTermsCode_display</a>

First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#shipToLine1 name="shipToLine1">shipToLine1</a>

Type the first line of the customer's shipping address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Street 1</td></tr><tr><td>description</td><td>Type the first line of the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_line1</td></tr></table>

### <a href=#shipToLine2 name="shipToLine2">shipToLine2</a>

Type the second line of the customer's shipping address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Street 2</td></tr><tr><td>description</td><td>Type the second line of the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_line2</td></tr></table>

### <a href=#shipToLine3 name="shipToLine3">shipToLine3</a>

Type the third line of the shipping address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Street 3</td></tr><tr><td>description</td><td>Type the third line of the shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_line3</td></tr></table>

### <a href=#shipToName name="shipToName">shipToName</a>

Type a name for the customer's shipping address, such as "Headquarters" or "Field office",  to identify the address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Name</td></tr><tr><td>description</td><td>Type a name for the customer's shipping address, such as "Headquarters" or "Field office",  to identify the address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_name</td></tr></table>

### <a href=#shipToPostalCode name="shipToPostalCode">shipToPostalCode</a>

Type the ZIP Code or postal code for the shipping address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To ZIP/Postal Code</td></tr><tr><td>description</td><td>Type the ZIP Code or postal code for the shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_postalcode</td></tr></table>

### <a href=#shipToStateOrProvince name="shipToStateOrProvince">shipToStateOrProvince</a>

Type the state or province for the shipping address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To State/Province</td></tr><tr><td>description</td><td>Type the state or province for the shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_stateorprovince</td></tr></table>

### <a href=#shipToTelephone name="shipToTelephone">shipToTelephone</a>

Type the phone number for the customer's shipping address.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To Phone</td></tr><tr><td>description</td><td>Type the phone number for the customer's shipping address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>shipto_telephone</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the quote is draft, active, won, or closed. Only draft quotes can be edited.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the quote is draft, active, won, or closed. Only draft quotes can be edited.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Draft</td><td>0</td></tr><tr><td>en</td><td>Active</td><td>1</td></tr><tr><td>en</td><td>Won</td><td>2</td></tr><tr><td>en</td><td>Closed</td><td>3</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the quote's status.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the quote's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>In Progress</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Open</td><td>3</td><td>1</td></tr><tr><td>en</td><td>Won</td><td>4</td><td>2</td></tr><tr><td>en</td><td>Lost</td><td>5</td><td>3</td></tr><tr><td>en</td><td>Canceled</td><td>6</td><td>3</td></tr><tr><td>en</td><td>Revised</td><td>7</td><td>3</td></tr><tr><td>en</td><td>In Progress</td><td>1</td><td>0</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#totalAmount name="totalAmount">totalAmount</a>

Shows the total amount due, calculated as the sum of the products, discounts, freight, and taxes for the quote.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Amount</td></tr><tr><td>description</td><td>Shows the total amount due, calculated as the sum of the products, discounts, freight, and taxes for the quote.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalamount</td></tr></table>

### <a href=#totalAmountBase name="totalAmountBase">totalAmountBase</a>

Value of the Total Amount in base currency.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Amount (Base)</td></tr><tr><td>description</td><td>Value of the Total Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalamount_base</td></tr></table>

### <a href=#totalAmountLessFreight name="totalAmountLessFreight">totalAmountLessFreight</a>

Shows the total product amount for the quote, minus any discounts. This value is added to freight and tax amounts in the calculation for the total amount due for the quote.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Pre-Freight Amount</td></tr><tr><td>description</td><td>Shows the total product amount for the quote, minus any discounts. This value is added to freight and tax amounts in the calculation for the total amount due for the quote.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalamountlessfreight</td></tr></table>

### <a href=#totalAmountLessFreightBase name="totalAmountLessFreightBase">totalAmountLessFreightBase</a>

Value of the Total Pre-Freight Amount in base currency.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Pre-Freight Amount (Base)</td></tr><tr><td>description</td><td>Value of the Total Pre-Freight Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalamountlessfreight_base</td></tr></table>

### <a href=#totalDiscountAmount name="totalDiscountAmount">totalDiscountAmount</a>

Shows the total discount amount, based on the discount price and rate entered on the quote.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Discount Amount</td></tr><tr><td>description</td><td>Shows the total discount amount, based on the discount price and rate entered on the quote.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totaldiscountamount</td></tr></table>

### <a href=#totalDiscountAmountBase name="totalDiscountAmountBase">totalDiscountAmountBase</a>

Value of the Total Discount Amount in base currency.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Discount Amount (Base)</td></tr><tr><td>description</td><td>Value of the Total Discount Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totaldiscountamount_base</td></tr></table>

### <a href=#totalLineItemAmount name="totalLineItemAmount">totalLineItemAmount</a>

Shows the sum of all existing and write-in products included on the quote, based on the specified price list and quantities.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Detail Amount</td></tr><tr><td>description</td><td>Shows the sum of all existing and write-in products included on the quote, based on the specified price list and quantities.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totallineitemamount</td></tr></table>

### <a href=#totalLineItemAmountBase name="totalLineItemAmountBase">totalLineItemAmountBase</a>

Value of the Total Detail Amount in base currency.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Detail Amount (Base)</td></tr><tr><td>description</td><td>Value of the Total Detail Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totallineitemamount_base</td></tr></table>

### <a href=#totalLineItemDiscountAmount name="totalLineItemDiscountAmount">totalLineItemDiscountAmount</a>

Shows the total of the Manual Discount amounts specified on all products included in the quote. This value is reflected in the Detail Amount field on the quote and is added to any discount amount or rate specified on the quote  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Line Item Discount Amount</td></tr><tr><td>description</td><td>Shows the total of the Manual Discount amounts specified on all products included in the quote. This value is reflected in the Detail Amount field on the quote and is added to any discount amount or rate specified on the quote</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totallineitemdiscountamount</td></tr></table>

### <a href=#totalLineItemDiscountAmountBase name="totalLineItemDiscountAmountBase">totalLineItemDiscountAmountBase</a>

Value of the Total Line Item Discount Amount in base currency.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Line Item Discount Amount (Base)</td></tr><tr><td>description</td><td>Value of the Total Line Item Discount Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totallineitemdiscountamount_base</td></tr></table>

### <a href=#totalTax name="totalTax">totalTax</a>

Shows the total of the Tax amounts specified on all products included in the quote, included in the Total Amount due calculation for the quote.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Tax</td></tr><tr><td>description</td><td>Shows the total of the Tax amounts specified on all products included in the quote, included in the Total Amount due calculation for the quote.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totaltax</td></tr></table>

### <a href=#totalTaxBase name="totalTaxBase">totalTaxBase</a>

Value of the Total Tax in base currency.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Tax (Base)</td></tr><tr><td>description</td><td>Value of the Total Tax in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totaltax_base</td></tr></table>

### <a href=#willCall name="willCall">willCall</a>

Select whether the products included in the quote should be shipped to the specified address or held until the customer calls with further pick up or delivery instructions.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ship To</td></tr><tr><td>description</td><td>Select whether the products included in the quote should be shipped to the specified address or held until the customer calls with further pick up or delivery instructions.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>willcall</td></tr></table>

### <a href=#onHoldTime name="onHoldTime">onHoldTime</a>

Shows the duration in minutes for which the quote was on hold.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Hold Time (Minutes)</td></tr><tr><td>description</td><td>Shows the duration in minutes for which the quote was on hold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>onholdtime</td></tr></table>

### <a href=#lastOnHoldTime name="lastOnHoldTime">lastOnHoldTime</a>

Contains the date time stamp of the last on hold time.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last On Hold Time</td></tr><tr><td>description</td><td>Contains the date time stamp of the last on hold time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastonholdtime</td></tr></table>

### <a href=#SLAId name="SLAId">SLAId</a>

Choose the service level agreement (SLA) that you want to apply to the quote record.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Choose the service level agreement (SLA) that you want to apply to the quote record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#SLAInvokedId name="SLAInvokedId">SLAInvokedId</a>

Last SLA that was applied to this quote. This field is for internal use only.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last SLA applied</td></tr><tr><td>description</td><td>Last SLA that was applied to this quote. This field is for internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slainvokedid</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Unique identifier of the account with which the quote is associated.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Unique identifier of the account with which the quote is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>accountid</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Unique identifier of the contact associated with the quote.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Unique identifier of the contact associated with the quote.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>contactid</td></tr></table>

### <a href=#campaignId name="campaignId">campaignId</a>

Shows the campaign that the order was created from.  
First included in: <a href="../../sales/Quote.md" target="_blank">sales/Quote</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source Campaign</td></tr><tr><td>description</td><td>Shows the campaign that the order was created from.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>campaignid</td></tr></table>

### <a href=#accountManagerId name="accountManagerId">accountManagerId</a>

Account manager responsible for the quote.  
First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account Manager</td></tr><tr><td>description</td><td>Account manager responsible for the quote.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_accountmanagerid</td></tr></table>

### <a href=#contractOrganizationalUnitId name="contractOrganizationalUnitId">contractOrganizationalUnitId</a>

The organizational unit in charge of the contract.  
First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contracting Unit</td></tr><tr><td>description</td><td>The organizational unit in charge of the contract.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_contractorganizationalunitid</td></tr></table>

### <a href=#feasible name="feasible">feasible</a>

Shows how the quote estimation compares to project estimation. Possible values are 0: Feasibility Not Available, 1: Feasible, and 2: Not Feasible.  
First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Feasibility</td></tr><tr><td>description</td><td>Shows how the quote estimation compares to project estimation. Possible values are 0: Feasibility Not Available, 1: Feasible, and 2: Not Feasible.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_feasible</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Feasibility Not Available</td><td>192350000</td></tr><tr><td>en</td><td>Feasible</td><td>192350001</td></tr><tr><td>en</td><td>Not Feasible</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#feasible_display name="feasible_display">feasible_display</a>

First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#orderType name="orderType">orderType</a>

Select whether the project contract is for an item-based or a work-based sale.  
First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>description</td><td>Select whether the project contract is for an item-based or a work-based sale.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_ordertype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Item based</td><td>192350000</td></tr><tr><td>en</td><td>Work based</td><td>192350001</td></tr></table></td></tr></table>

### <a href=#orderType_display name="orderType_display">orderType_display</a>

First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#adjustedGrossMargin name="adjustedGrossMargin">adjustedGrossMargin</a>

Shows the estimated gross margin after accounting for non-chargeable components.  
First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjusted Gross Margin (%)</td></tr><tr><td>description</td><td>Shows the estimated gross margin after accounting for non-chargeable components.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_adjustedgrossmargin</td></tr></table>

### <a href=#competitive name="competitive">competitive</a>

Shows how the quote estimation of sales value and schedule compare to customer expectations on those parameters. Possible values are 1: Within Customer expectations, 2: Not Within Customer expectations, and 0: Customer expectations Not Available.  
First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Competitive</td></tr><tr><td>description</td><td>Shows how the quote estimation of sales value and schedule compare to customer expectations on those parameters. Possible values are 1: Within Customer expectations, 2: Not Within Customer expectations, and 0: Customer expectations Not Available.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_competitive</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Customer Budget Not Available</td><td>192350000</td></tr><tr><td>en</td><td>Within Customer Expectations</td><td>192350001</td></tr><tr><td>en</td><td>Outside Customer Expectations</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#competitive_display name="competitive_display">competitive_display</a>

First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#customerBudgetRollUp name="customerBudgetRollUp">customerBudgetRollUp</a>

Shows the total customer budget for the quote, computed from all the quote lines.  
First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Budget</td></tr><tr><td>description</td><td>Shows the total customer budget for the quote, computed from all the quote lines.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_customerbudgetrollup</td></tr></table>

### <a href=#customerBudgetRollupBase name="customerBudgetRollupBase">customerBudgetRollupBase</a>

Shows the value of the customer budget in the base currency.  
First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Budget (Base)</td></tr><tr><td>description</td><td>Shows the value of the customer budget in the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_customerbudgetrollup_base</td></tr></table>

### <a href=#estimatedBudget name="estimatedBudget">estimatedBudget</a>

Shows how the estimated sales value on the quote compares to customer budgets. Possible values are 1: Within Customer Budget, 2: Exceeds Customer Budget, 0: Budget Estimate Not Available  
First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Budget</td></tr><tr><td>description</td><td>Shows how the estimated sales value on the quote compares to customer budgets. Possible values are 1: Within Customer Budget, 2: Exceeds Customer Budget, 0: Budget Estimate Not Available</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estimatedbudget</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Budget Estimate Not Available</td><td>192350000</td></tr><tr><td>en</td><td>Within Customer Budget</td><td>192350001</td></tr><tr><td>en</td><td>Exceeds Customer Budget</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#estimatedBudget_display name="estimatedBudget_display">estimatedBudget_display</a>

First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#estimatedCompletionRollUp name="estimatedCompletionRollUp">estimatedCompletionRollUp</a>

Estimated completion date, computed from the details of each quote line.  
First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Completion</td></tr><tr><td>description</td><td>Estimated completion date, computed from the details of each quote line.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estimatedcompletionrollup</td></tr></table>

### <a href=#estimatedSchedule name="estimatedSchedule">estimatedSchedule</a>

Shows how the estimated schedule on the quote compares to customer expectations. Possible values are 1: Estimated To Finish Early, 2: Estimated To Finish Late, 3: Estimated To Finish On Schedule, and 0: Schedule Not Available.  
First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Estimated Schedule</td></tr><tr><td>description</td><td>Shows how the estimated schedule on the quote compares to customer expectations. Possible values are 1: Estimated To Finish Early, 2: Estimated To Finish Late, 3: Estimated To Finish On Schedule, and 0: Schedule Not Available.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_estimatedschedule</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Schedule Not Available</td><td>192350000</td></tr><tr><td>en</td><td>Estimated To Finish Early</td><td>192350001</td></tr><tr><td>en</td><td>Estimated To Finish Late</td><td>192350002</td></tr><tr><td>en</td><td>Estimated To Finish On Schedule</td><td>192350003</td></tr></table></td></tr></table>

### <a href=#estimatedSchedule_display name="estimatedSchedule_display">estimatedSchedule_display</a>

First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#grossMargin name="grossMargin">grossMargin</a>

Shows the estimated gross margin without accounting for non-chargeable components.  
First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Gross Margin (%)</td></tr><tr><td>description</td><td>Shows the estimated gross margin without accounting for non-chargeable components.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_grossmargin</td></tr></table>

### <a href=#profitability name="profitability">profitability</a>

Shows the estimated profitability of the quote. Possible values are Profitable, Not Profitable, and Profitability not available.  
First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Profitability</td></tr><tr><td>description</td><td>Shows the estimated profitability of the quote. Possible values are Profitable, Not Profitable, and Profitability not available.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_profitability</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Profitability Not Available</td><td>192350000</td></tr><tr><td>en</td><td>Profitable</td><td>192350001</td></tr><tr><td>en</td><td>Not Profitable</td><td>192350002</td></tr></table></td></tr></table>

### <a href=#profitability_display name="profitability_display">profitability_display</a>

First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#totalChargeableCostRollup name="totalChargeableCostRollup">totalChargeableCostRollup</a>

First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Chargeable Cost</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_totalchargeablecostrollup</td></tr></table>

### <a href=#totalChargeableCostRollupBase name="totalChargeableCostRollupBase">totalChargeableCostRollupBase</a>

Value of the Total Chargeable Cost in base currency.  
First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Chargeable Cost (Base)</td></tr><tr><td>description</td><td>Value of the Total Chargeable Cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_totalchargeablecostrollup_base</td></tr></table>

### <a href=#totalNonchargeableCostRollup name="totalNonchargeableCostRollup">totalNonchargeableCostRollup</a>

First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Non-chargeable Cost</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_totalnonchargeablecostrollup</td></tr></table>

### <a href=#totalNonchargeableCostRollupBase name="totalNonchargeableCostRollupBase">totalNonchargeableCostRollupBase</a>

Value of the Total Non-chargeable Cost in base currency.  
First included in: projectServiceAutomation/Quote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Non-chargeable Cost (Base)</td></tr><tr><td>description</td><td>Value of the Total Non-chargeable Cost in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msdyn_totalnonchargeablecostrollup_base</td></tr></table>
