---
title: Opportunity - Common Data Model | Microsoft Docs
description: This describes the Opportunity entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Opportunity

A potential revenue-generating event or a sale to an account, which must be tracked through a sales process to completion.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/financialServices/banking/Opportunity.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/financialServices/banking/Opportunity  
- [/foundationCommon/crmCommon/sales/Opportunity](../../../sales/Opportunity.md "/core/applicationCommon/foundationCommon/crmCommon/sales/Opportunity.cdm.json/Opportunity")  
- [/foundationCommon/crmCommon/accelerators/nonProfit/Opportunity](../../nonProfit/Opportunity.md "/core/applicationCommon/foundationCommon/crmCommon/accelerators/nonProfit/Opportunity.cdm.json/Opportunity")  
- [/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/Opportunity](../../../projectCommon/projectServiceAutomation/Opportunity.md "/core/applicationCommon/foundationCommon/crmCommon/projectCommon/projectServiceAutomation/Opportunity.cdm.json/Opportunity")  
- [/foundationCommon/crmCommon/solutions/portals/Opportunity](../../../solutions/portals/Opportunity.md "/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Opportunity.cdm.json/Opportunity")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[ownerId](#ownerId)|Owner Id|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[opportunityId](#opportunityId)|Unique identifier of the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[emailAddress](#emailAddress)|The primary email address for the entity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[name](#name)|Type a subject or descriptive name, such as the expected order or company name, for the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[actualCloseDate](#actualCloseDate)|Shows the date and time when the opportunity was closed or canceled.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[actualValue](#actualValue)|Type the actual revenue amount for the opportunity for reporting and analysis of estimated versus actual sales. Field defaults to the Est. Revenue value when an opportunity is won.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[actualValueBase](#actualValueBase)|Value of the Actual Revenue in base currency.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[budgetAmount](#budgetAmount)|Type a value between 0 and 1,000,000,000,000 to indicate the lead's potential available budget.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[budgetAmountBase](#budgetAmountBase)|Value of the Budget Amount in base currency.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[budgetStatus](#budgetStatus)|Select the likely budget status for the lead's company. This may help determine the lead rating or your sales approach.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[budgetStatus_display](#budgetStatus_display)||<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[closeProbability](#closeProbability)|Type a number from 0 to 100 that represents the likelihood of closing the opportunity. This can aid the sales team in their efforts to convert the opportunity in a sale.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[completeInternalReview](#completeInternalReview)|Select whether an internal review has been completed for this opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[confirmInterest](#confirmInterest)|Select whether the lead confirmed interest in your offerings. This helps in determining the lead quality and the probability of it turning into an opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[currentSituation](#currentSituation)|Type notes about the company or organization associated with the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[customerIdType](#customerIdType)|The type of customer, either Account or Contact.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[customerId](#customerId)|The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[customerNeed](#customerNeed)|Type some notes about the customer's requirements, to help the sales team identify products and services that could meet their requirements.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[customerPainPoints](#customerPainPoints)|Type notes about the customer's pain points to help the sales team identify products and services that could address these pain points.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[decisionMaker](#decisionMaker)|Select whether your notes include information about who makes the purchase decisions at the lead's company.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[description](#description)|Type additional information to describe the opportunity, such as possible products to sell or past purchases from the customer.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[developProposal](#developProposal)|Select whether a proposal has been developed for the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[discountAmount](#discountAmount)|Type the discount amount for the opportunity if the customer is eligible for special savings.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[discountAmountBase](#discountAmountBase)|Value of the Opportunity Discount Amount in base currency.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[discountPercentage](#discountPercentage)|Type the discount rate that should be applied to the Product Totals field to include additional savings for the customer in the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[estimatedCloseDate](#estimatedCloseDate)|Enter the expected closing date of the opportunity to help make accurate revenue forecasts.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[estimatedValue](#estimatedValue)|Type the estimated revenue amount to indicate the potential sale or value of the opportunity for revenue forecasting. This field can be either system-populated or editable based on the selection in the Revenue field.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[estimatedValueBase](#estimatedValueBase)|Value of the Est. Revenue in base currency.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[evaluateFit](#evaluateFit)|Select whether the fit between the lead's requirements and your offerings was evaluated.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[resolveFeedback](#resolveFeedback)|Choose whether the proposal feedback has been captured and resolved for the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[fileDebrief](#fileDebrief)|Choose whether the sales team has recorded detailed notes on the proposals and the account's responses.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[completeFinalProposal](#completeFinalProposal)|Select whether a final proposal has been completed for the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[finalDecisionDate](#finalDecisionDate)|Enter the date and time when the final decision of the opportunity was made.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[freightAmount](#freightAmount)|Type the cost of freight or shipping for the products included in the opportunity for use in calculating the Total Amount field.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[freightAmountBase](#freightAmountBase)|Value of the Freight Amount in base currency.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[initialCommunication](#initialCommunication)|Choose whether someone from the sales team contacted this lead earlier.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[initialCommunication_display](#initialCommunication_display)||<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[isRevenueSystemCalculated](#isRevenueSystemCalculated)|Select whether the estimated revenue for the opportunity is calculated automatically based on the products entered or entered manually by a user.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[need](#need)|Choose how high the level of need is for the lead's company.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[need_display](#need_display)||<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[opportunityRatingCode](#opportunityRatingCode)|Select the expected value or priority of the opportunity based on revenue, customer status, or closing probability.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[opportunityRatingCode_display](#opportunityRatingCode_display)||<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[parentAccountId](#parentAccountId)|Choose an account to connect this opportunity to, so that the relationship is visible in reports and analytics, and to provide a quick link to additional details, such as financial information and activities.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[parentContactId](#parentContactId)|Choose a contact to connect this opportunity to, so that the relationship is visible in reports and analytics.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[participatesInWorkflow](#participatesInWorkflow)|Information about whether the opportunity participates in workflow rules.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[priceLevelId](#priceLevelId)|Choose the price list associated with this record to make sure the products associated with the campaign are offered at the correct prices.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[pricingErrorCode](#pricingErrorCode)|Pricing error for the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[pricingErrorCode_display](#pricingErrorCode_display)||<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[priorityCode](#priorityCode)|Select the priority so that preferred customers or critical issues are handled quickly.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[priorityCode_display](#priorityCode_display)||<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[purchaseProcess](#purchaseProcess)|Choose whether an individual or a committee will be involved in the  purchase process for the lead.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[purchaseProcess_display](#purchaseProcess_display)||<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[purchaseTimeFrame](#purchaseTimeFrame)|Choose how long the lead will likely take to make the purchase.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[purchaseTimeFrame_display](#purchaseTimeFrame_display)||<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[salesStage](#salesStage)|Select the sales stage of this opportunity to aid the sales team in their efforts to win this opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[salesStage_display](#salesStage_display)||<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[salesStageCode](#salesStageCode)|Select the sales process stage for the opportunity to indicate the probability of closing the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[salesStageCode_display](#salesStageCode_display)||<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[presentProposal](#presentProposal)|Select whether a proposal for the opportunity has been presented to the account.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[captureProposalFeedback](#captureProposalFeedback)|Choose whether the proposal feedback has been captured for the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[proposedSolution](#proposedSolution)|Type notes about the proposed solution for the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[pursuitDecision](#pursuitDecision)|Select whether the decision about pursuing the opportunity has been made.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[qualificationComments](#qualificationComments)|Type comments about the qualification or scoring of the lead.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[quoteComments](#quoteComments)|Type comments about the quotes associated with the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[sendThankYouNote](#sendThankYouNote)|Select whether a thank you note has been sent to the account for considering the proposal.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[scheduleFollowupProspect](#scheduleFollowupProspect)|Enter the date and time of the prospecting follow-up meeting with the lead.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[scheduleFollowUpQualify](#scheduleFollowUpQualify)|Enter the date and time of the qualifying follow-up meeting with the lead.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[scheduleProposalMeeting](#scheduleProposalMeeting)|Enter the date and time of the proposal meeting for the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[stateCode](#stateCode)|Shows whether the opportunity is open, won, or lost. Won and lost opportunities are read-only and can't be edited until they are reactivated.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[stateCode_display](#stateCode_display)||<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[statusCode](#statusCode)|Select the opportunity's status.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[statusCode_display](#statusCode_display)||<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[stepId](#stepId)|Shows the ID of the workflow step.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[stepName](#stepName)|Shows the current phase in the sales pipeline for the opportunity. This is updated by a workflow.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[timeLine](#timeLine)|Select when the opportunity is likely to be closed.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[timeLine_display](#timeLine_display)||<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[totalAmount](#totalAmount)|Shows the total amount due, calculated as the sum of the products, discounts, freight, and taxes for the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[totalAmountBase](#totalAmountBase)|Value of the Total Amount in base currency.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[totalAmountLessFreight](#totalAmountLessFreight)|Shows the total product amount for the opportunity, minus any discounts. This value is added to freight and tax amounts in the calculation for the total amount of the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[totalAmountLessFreightBase](#totalAmountLessFreightBase)|Value of the Total Pre-Freight Amount in base currency.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[totalDiscountAmount](#totalDiscountAmount)|Shows the total discount amount, based on the discount price and rate entered on the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[totalDiscountAmountBase](#totalDiscountAmountBase)|Value of the Total Discount Amount in base currency.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[totalLineItemAmount](#totalLineItemAmount)|Shows the sum of all existing and write-in products included on the opportunity, based on the specified price list and quantities.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[totalLineItemAmountBase](#totalLineItemAmountBase)|Value of the Total Detail Amount in base currency.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[totalLineItemDiscountAmount](#totalLineItemDiscountAmount)|Shows the total of the Manual Discount amounts specified on all products included in the opportunity. This value is reflected in the Total Detail Amount field on the opportunity and is added to any discount amount or rate specified on the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[totalLineItemDiscountAmountBase](#totalLineItemDiscountAmountBase)|Value of the Total Line Item Discount Amount in base currency.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[totalTax](#totalTax)|Shows the total of the Tax amounts specified on all products included in the opportunity, included in the Total Amount field calculation for the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[totalTaxBase](#totalTaxBase)|Value of the Total Tax in base currency.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[identifyCustomerContacts](#identifyCustomerContacts)|Select whether the customer contacts for this opportunity have been identified.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[identifyCompetitors](#identifyCompetitors)|Select whether information about competitors is included.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[identifyPursuitTeam](#identifyPursuitTeam)|Choose whether you have recorded who will pursue the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[presentFinalProposal](#presentFinalProposal)|Select whether the final proposal has been presented to the account.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[onHoldTime](#onHoldTime)|Shows the duration in minutes for which the opportunity was on hold.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[lastOnHoldTime](#lastOnHoldTime)|Contains the date time stamp of the last on hold time.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[SLAId](#SLAId)|Choose the service level agreement (SLA) that you want to apply to the opportunity record.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[SLAInvokedId](#SLAInvokedId)|Last SLA that was applied to this opportunity. This field is for internal use only.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[timeSpentByMeOnEmailAndMeetings](#timeSpentByMeOnEmailAndMeetings)|Total time spent for emails (read and write) and meetings by me in relation to the opportunity record.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[originatingLeadId](#originatingLeadId)|Choose the lead that the opportunity was created from for reporting and analytics. The field is read-only after the opportunity is created and defaults to the correct lead when an opportunity is created from a converted lead.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[accountId](#accountId)|Unique identifier of the account with which the opportunity is associated.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[contactId](#contactId)|Unique identifier of the contact associated with the opportunity.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[campaignId](#campaignId)|Shows the campaign that the opportunity was created from. The ID is used for tracking the success of the campaign.|<a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>|
|[costOfProperty](#costOfProperty)|The price of the property for which customer is applying for the loan.|<a href="Opportunity.md" target="_blank">banking/Opportunity</a>|
|[costOfPropertyBase](#costOfPropertyBase)|Value of the Cost of Property in base currency.|<a href="Opportunity.md" target="_blank">banking/Opportunity</a>|
|[downPayment](#downPayment)|The total down payment that customer has made against the car or property for which he is applying for the loan.|<a href="Opportunity.md" target="_blank">banking/Opportunity</a>|
|[downPaymentBase](#downPaymentBase)|Value of the Down Payment in base currency.|<a href="Opportunity.md" target="_blank">banking/Opportunity</a>|
|[interestRate](#interestRate)|The rate of interest applicable to the product. The applicable rate must be fetched from the product catalog based on the requested amount.|<a href="Opportunity.md" target="_blank">banking/Opportunity</a>|
|[preferredFollowUpTime](#preferredFollowUpTime)|Convenient time for the customer to be contacted.|<a href="Opportunity.md" target="_blank">banking/Opportunity</a>|
|[preferredFollowUpTime_display](#preferredFollowUpTime_display)||<a href="Opportunity.md" target="_blank">banking/Opportunity</a>|
|[productId](#productId)|The product that the customer is applying for.|<a href="Opportunity.md" target="_blank">banking/Opportunity</a>|
|[purposeOfLoan](#purposeOfLoan)|The reason or purpose for which customer is applying for the loan.|<a href="Opportunity.md" target="_blank">banking/Opportunity</a>|
|[requestedAmount](#requestedAmount)|The amount of the product that customer is applying for such as the loan amount or card limit.|<a href="Opportunity.md" target="_blank">banking/Opportunity</a>|
|[requestedAmountBase](#requestedAmountBase)|Value of the Requested Amount in base currency.|<a href="Opportunity.md" target="_blank">banking/Opportunity</a>|
|[termOfLoan](#termOfLoan)|The number of months that customer is requesting as term of the loan.|<a href="Opportunity.md" target="_blank">banking/Opportunity</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#opportunityId name="opportunityId">opportunityId</a>

Unique identifier of the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Opportunity</td></tr><tr><td>description</td><td>Unique identifier of the opportunity.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>opportunityid</td></tr></table>

### <a href=#emailAddress name="emailAddress">emailAddress</a>

The primary email address for the entity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Address</td></tr><tr><td>description</td><td>The primary email address for the entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>emailaddress</td></tr></table>

### <a href=#name name="name">name</a>

Type a subject or descriptive name, such as the expected order or company name, for the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Topic</td></tr><tr><td>description</td><td>Type a subject or descriptive name, such as the expected order or company name, for the opportunity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>300</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#actualCloseDate name="actualCloseDate">actualCloseDate</a>

Shows the date and time when the opportunity was closed or canceled.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Close Date</td></tr><tr><td>description</td><td>Shows the date and time when the opportunity was closed or canceled.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualclosedate</td></tr></table>

### <a href=#actualValue name="actualValue">actualValue</a>

Type the actual revenue amount for the opportunity for reporting and analysis of estimated versus actual sales. Field defaults to the Est. Revenue value when an opportunity is won.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Revenue</td></tr><tr><td>description</td><td>Type the actual revenue amount for the opportunity for reporting and analysis of estimated versus actual sales. Field defaults to the Est. Revenue value when an opportunity is won.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>-1000000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualvalue</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#actualValueBase name="actualValueBase">actualValueBase</a>

Value of the Actual Revenue in base currency.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual Revenue (Base)</td></tr><tr><td>description</td><td>Value of the Actual Revenue in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualvalue_base</td></tr></table>

### <a href=#budgetAmount name="budgetAmount">budgetAmount</a>

Type a value between 0 and 1,000,000,000,000 to indicate the lead's potential available budget.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget Amount</td></tr><tr><td>description</td><td>Type a value between 0 and 1,000,000,000,000 to indicate the lead's potential available budget.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>budgetamount</td></tr></table>

### <a href=#budgetAmountBase name="budgetAmountBase">budgetAmountBase</a>

Value of the Budget Amount in base currency.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget Amount (Base)</td></tr><tr><td>description</td><td>Value of the Budget Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>budgetamount_base</td></tr></table>

### <a href=#budgetStatus name="budgetStatus">budgetStatus</a>

Select the likely budget status for the lead's company. This may help determine the lead rating or your sales approach.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget</td></tr><tr><td>description</td><td>Select the likely budget status for the lead's company. This may help determine the lead rating or your sales approach.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>budgetstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#budgetStatus_display name="budgetStatus_display">budgetStatus_display</a>

First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#closeProbability name="closeProbability">closeProbability</a>

Type a number from 0 to 100 that represents the likelihood of closing the opportunity. This can aid the sales team in their efforts to convert the opportunity in a sale.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Probability</td></tr><tr><td>description</td><td>Type a number from 0 to 100 that represents the likelihood of closing the opportunity. This can aid the sales team in their efforts to convert the opportunity in a sale.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>closeprobability</td></tr></table>

### <a href=#completeInternalReview name="completeInternalReview">completeInternalReview</a>

Select whether an internal review has been completed for this opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Complete Internal Review</td></tr><tr><td>description</td><td>Select whether an internal review has been completed for this opportunity.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>completeinternalreview</td></tr></table>

### <a href=#confirmInterest name="confirmInterest">confirmInterest</a>

Select whether the lead confirmed interest in your offerings. This helps in determining the lead quality and the probability of it turning into an opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Confirm Interest</td></tr><tr><td>description</td><td>Select whether the lead confirmed interest in your offerings. This helps in determining the lead quality and the probability of it turning into an opportunity.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>confirminterest</td></tr></table>

### <a href=#currentSituation name="currentSituation">currentSituation</a>

Type notes about the company or organization associated with the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current Situation</td></tr><tr><td>description</td><td>Type notes about the company or organization associated with the opportunity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>currentsituation</td></tr></table>

### <a href=#customerIdType name="customerIdType">customerIdType</a>

The type of customer, either Account or Contact.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>The type of customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>customeridtype</td></tr></table>

### <a href=#customerId name="customerId">customerId</a>

The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerid</td></tr></table>

### <a href=#customerNeed name="customerNeed">customerNeed</a>

Type some notes about the customer's requirements, to help the sales team identify products and services that could meet their requirements.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Need</td></tr><tr><td>description</td><td>Type some notes about the customer's requirements, to help the sales team identify products and services that could meet their requirements.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerneed</td></tr></table>

### <a href=#customerPainPoints name="customerPainPoints">customerPainPoints</a>

Type notes about the customer's pain points to help the sales team identify products and services that could address these pain points.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Pain Points</td></tr><tr><td>description</td><td>Type notes about the customer's pain points to help the sales team identify products and services that could address these pain points.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerpainpoints</td></tr></table>

### <a href=#decisionMaker name="decisionMaker">decisionMaker</a>

Select whether your notes include information about who makes the purchase decisions at the lead's company.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Decision Maker?</td></tr><tr><td>description</td><td>Select whether your notes include information about who makes the purchase decisions at the lead's company.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>decisionmaker</td></tr></table>

### <a href=#description name="description">description</a>

Type additional information to describe the opportunity, such as possible products to sell or past purchases from the customer.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>Type additional information to describe the opportunity, such as possible products to sell or past purchases from the customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>description</td></tr></table>

### <a href=#developProposal name="developProposal">developProposal</a>

Select whether a proposal has been developed for the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Develop Proposal</td></tr><tr><td>description</td><td>Select whether a proposal has been developed for the opportunity.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>developproposal</td></tr></table>

### <a href=#discountAmount name="discountAmount">discountAmount</a>

Type the discount amount for the opportunity if the customer is eligible for special savings.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Opportunity Discount Amount</td></tr><tr><td>description</td><td>Type the discount amount for the opportunity if the customer is eligible for special savings.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>discountamount</td></tr></table>

### <a href=#discountAmountBase name="discountAmountBase">discountAmountBase</a>

Value of the Opportunity Discount Amount in base currency.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Opportunity Discount Amount (Base)</td></tr><tr><td>description</td><td>Value of the Opportunity Discount Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>discountamount_base</td></tr></table>

### <a href=#discountPercentage name="discountPercentage">discountPercentage</a>

Type the discount rate that should be applied to the Product Totals field to include additional savings for the customer in the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Opportunity Discount (%)</td></tr><tr><td>description</td><td>Type the discount rate that should be applied to the Product Totals field to include additional savings for the customer in the opportunity.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>discountpercentage</td></tr></table>

### <a href=#estimatedCloseDate name="estimatedCloseDate">estimatedCloseDate</a>

Enter the expected closing date of the opportunity to help make accurate revenue forecasts.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Est. Close Date</td></tr><tr><td>description</td><td>Enter the expected closing date of the opportunity to help make accurate revenue forecasts.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>estimatedclosedate</td></tr></table>

### <a href=#estimatedValue name="estimatedValue">estimatedValue</a>

Type the estimated revenue amount to indicate the potential sale or value of the opportunity for revenue forecasting. This field can be either system-populated or editable based on the selection in the Revenue field.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Est. Revenue</td></tr><tr><td>description</td><td>Type the estimated revenue amount to indicate the potential sale or value of the opportunity for revenue forecasting. This field can be either system-populated or editable based on the selection in the Revenue field.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>-1000000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>estimatedvalue</td></tr></table>

### <a href=#estimatedValueBase name="estimatedValueBase">estimatedValueBase</a>

Value of the Est. Revenue in base currency.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Est. Revenue (Base)</td></tr><tr><td>description</td><td>Value of the Est. Revenue in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>estimatedvalue_base</td></tr></table>

### <a href=#evaluateFit name="evaluateFit">evaluateFit</a>

Select whether the fit between the lead's requirements and your offerings was evaluated.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Evaluate Fit</td></tr><tr><td>description</td><td>Select whether the fit between the lead's requirements and your offerings was evaluated.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>evaluatefit</td></tr></table>

### <a href=#resolveFeedback name="resolveFeedback">resolveFeedback</a>

Choose whether the proposal feedback has been captured and resolved for the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Feedback Resolved</td></tr><tr><td>description</td><td>Choose whether the proposal feedback has been captured and resolved for the opportunity.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>resolvefeedback</td></tr></table>

### <a href=#fileDebrief name="fileDebrief">fileDebrief</a>

Choose whether the sales team has recorded detailed notes on the proposals and the account's responses.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>File Debrief</td></tr><tr><td>description</td><td>Choose whether the sales team has recorded detailed notes on the proposals and the account's responses.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>filedebrief</td></tr></table>

### <a href=#completeFinalProposal name="completeFinalProposal">completeFinalProposal</a>

Select whether a final proposal has been completed for the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Final Proposal Ready</td></tr><tr><td>description</td><td>Select whether a final proposal has been completed for the opportunity.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>completefinalproposal</td></tr></table>

### <a href=#finalDecisionDate name="finalDecisionDate">finalDecisionDate</a>

Enter the date and time when the final decision of the opportunity was made.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Final Decision Date</td></tr><tr><td>description</td><td>Enter the date and time when the final decision of the opportunity was made.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>finaldecisiondate</td></tr></table>

### <a href=#freightAmount name="freightAmount">freightAmount</a>

Type the cost of freight or shipping for the products included in the opportunity for use in calculating the Total Amount field.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freight Amount</td></tr><tr><td>description</td><td>Type the cost of freight or shipping for the products included in the opportunity for use in calculating the Total Amount field.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>freightamount</td></tr></table>

### <a href=#freightAmountBase name="freightAmountBase">freightAmountBase</a>

Value of the Freight Amount in base currency.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freight Amount (Base)</td></tr><tr><td>description</td><td>Value of the Freight Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>freightamount_base</td></tr></table>

### <a href=#initialCommunication name="initialCommunication">initialCommunication</a>

Choose whether someone from the sales team contacted this lead earlier.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Initial Communication</td></tr><tr><td>description</td><td>Choose whether someone from the sales team contacted this lead earlier.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>initialcommunication</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#initialCommunication_display name="initialCommunication_display">initialCommunication_display</a>

First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isRevenueSystemCalculated name="isRevenueSystemCalculated">isRevenueSystemCalculated</a>

Select whether the estimated revenue for the opportunity is calculated automatically based on the products entered or entered manually by a user.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Revenue</td></tr><tr><td>description</td><td>Select whether the estimated revenue for the opportunity is calculated automatically based on the products entered or entered manually by a user.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isrevenuesystemcalculated</td></tr></table>

### <a href=#need name="need">need</a>

Choose how high the level of need is for the lead's company.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Need</td></tr><tr><td>description</td><td>Choose how high the level of need is for the lead's company.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>need</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#need_display name="need_display">need_display</a>

First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#opportunityRatingCode name="opportunityRatingCode">opportunityRatingCode</a>

Select the expected value or priority of the opportunity based on revenue, customer status, or closing probability.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rating</td></tr><tr><td>description</td><td>Select the expected value or priority of the opportunity based on revenue, customer status, or closing probability.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>opportunityratingcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Hot</td><td>1</td></tr><tr><td>en</td><td>Warm</td><td>2</td></tr><tr><td>en</td><td>Cold</td><td>3</td></tr></table></td></tr></table>

### <a href=#opportunityRatingCode_display name="opportunityRatingCode_display">opportunityRatingCode_display</a>

First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#parentAccountId name="parentAccountId">parentAccountId</a>

Choose an account to connect this opportunity to, so that the relationship is visible in reports and analytics, and to provide a quick link to additional details, such as financial information and activities.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account</td></tr><tr><td>description</td><td>Choose an account to connect this opportunity to, so that the relationship is visible in reports and analytics, and to provide a quick link to additional details, such as financial information and activities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentaccountid</td></tr></table>

### <a href=#parentContactId name="parentContactId">parentContactId</a>

Choose a contact to connect this opportunity to, so that the relationship is visible in reports and analytics.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>description</td><td>Choose a contact to connect this opportunity to, so that the relationship is visible in reports and analytics.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentcontactid</td></tr></table>

### <a href=#participatesInWorkflow name="participatesInWorkflow">participatesInWorkflow</a>

Information about whether the opportunity participates in workflow rules.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Participates in Workflow</td></tr><tr><td>description</td><td>Information about whether the opportunity participates in workflow rules.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>participatesinworkflow</td></tr></table>

### <a href=#priceLevelId name="priceLevelId">priceLevelId</a>

Choose the price list associated with this record to make sure the products associated with the campaign are offered at the correct prices.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price List</td></tr><tr><td>description</td><td>Choose the price list associated with this record to make sure the products associated with the campaign are offered at the correct prices.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>pricelevelid</td></tr></table>

### <a href=#pricingErrorCode name="pricingErrorCode">pricingErrorCode</a>

Pricing error for the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pricing Error </td></tr><tr><td>description</td><td>Pricing error for the opportunity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>pricingerrorcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>0</td></tr><tr><td>en</td><td>Detail Error</td><td>1</td></tr><tr><td>en</td><td>Missing Price Level</td><td>2</td></tr><tr><td>en</td><td>Inactive Price Level</td><td>3</td></tr><tr><td>en</td><td>Missing Quantity</td><td>4</td></tr><tr><td>en</td><td>Missing Unit Price</td><td>5</td></tr><tr><td>en</td><td>Missing Product</td><td>6</td></tr><tr><td>en</td><td>Invalid Product</td><td>7</td></tr><tr><td>en</td><td>Missing Pricing Code</td><td>8</td></tr><tr><td>en</td><td>Invalid Pricing Code</td><td>9</td></tr><tr><td>en</td><td>Missing UOM</td><td>10</td></tr><tr><td>en</td><td>Product Not In Price Level</td><td>11</td></tr><tr><td>en</td><td>Missing Price Level Amount</td><td>12</td></tr><tr><td>en</td><td>Missing Price Level Percentage</td><td>13</td></tr><tr><td>en</td><td>Missing Price</td><td>14</td></tr><tr><td>en</td><td>Missing Current Cost</td><td>15</td></tr><tr><td>en</td><td>Missing Standard Cost</td><td>16</td></tr><tr><td>en</td><td>Invalid Price Level Amount</td><td>17</td></tr><tr><td>en</td><td>Invalid Price Level Percentage</td><td>18</td></tr><tr><td>en</td><td>Invalid Price</td><td>19</td></tr><tr><td>en</td><td>Invalid Current Cost</td><td>20</td></tr><tr><td>en</td><td>Invalid Standard Cost</td><td>21</td></tr><tr><td>en</td><td>Invalid Rounding Policy</td><td>22</td></tr><tr><td>en</td><td>Invalid Rounding Option</td><td>23</td></tr><tr><td>en</td><td>Invalid Rounding Amount</td><td>24</td></tr><tr><td>en</td><td>Price Calculation Error</td><td>25</td></tr><tr><td>en</td><td>Invalid Discount Type</td><td>26</td></tr><tr><td>en</td><td>Discount Type Invalid State</td><td>27</td></tr><tr><td>en</td><td>Invalid Discount</td><td>28</td></tr><tr><td>en</td><td>Invalid Quantity</td><td>29</td></tr><tr><td>en</td><td>Invalid Pricing Precision</td><td>30</td></tr><tr><td>en</td><td>Missing Product Default UOM</td><td>31</td></tr><tr><td>en</td><td>Missing Product UOM Schedule </td><td>32</td></tr><tr><td>en</td><td>Inactive Discount Type</td><td>33</td></tr><tr><td>en</td><td>Invalid Price Level Currency</td><td>34</td></tr><tr><td>en</td><td>Price Attribute Out Of Range</td><td>35</td></tr><tr><td>en</td><td>Base Currency Attribute Overflow</td><td>36</td></tr><tr><td>en</td><td>Base Currency Attribute Underflow</td><td>37</td></tr></table></td></tr></table>

### <a href=#pricingErrorCode_display name="pricingErrorCode_display">pricingErrorCode_display</a>

First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#priorityCode name="priorityCode">priorityCode</a>

Select the priority so that preferred customers or critical issues are handled quickly.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>description</td><td>Select the priority so that preferred customers or critical issues are handled quickly.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>prioritycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#priorityCode_display name="priorityCode_display">priorityCode_display</a>

First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#purchaseProcess name="purchaseProcess">purchaseProcess</a>

Choose whether an individual or a committee will be involved in the  purchase process for the lead.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase Process</td></tr><tr><td>description</td><td>Choose whether an individual or a committee will be involved in the  purchase process for the lead.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>purchaseprocess</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#purchaseProcess_display name="purchaseProcess_display">purchaseProcess_display</a>

First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#purchaseTimeFrame name="purchaseTimeFrame">purchaseTimeFrame</a>

Choose how long the lead will likely take to make the purchase.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase Timeframe</td></tr><tr><td>description</td><td>Choose how long the lead will likely take to make the purchase.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>purchasetimeframe</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#purchaseTimeFrame_display name="purchaseTimeFrame_display">purchaseTimeFrame_display</a>

First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#salesStage name="salesStage">salesStage</a>

Select the sales stage of this opportunity to aid the sales team in their efforts to win this opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales Stage</td></tr><tr><td>description</td><td>Select the sales stage of this opportunity to aid the sales team in their efforts to win this opportunity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>salesstage</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Qualify</td><td>0</td></tr><tr><td>en</td><td>Develop</td><td>1</td></tr><tr><td>en</td><td>Propose</td><td>2</td></tr><tr><td>en</td><td>Close</td><td>3</td></tr></table></td></tr></table>

### <a href=#salesStage_display name="salesStage_display">salesStage_display</a>

First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#salesStageCode name="salesStageCode">salesStageCode</a>

Select the sales process stage for the opportunity to indicate the probability of closing the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Code</td></tr><tr><td>description</td><td>Select the sales process stage for the opportunity to indicate the probability of closing the opportunity.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>salesstagecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#salesStageCode_display name="salesStageCode_display">salesStageCode_display</a>

First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#presentProposal name="presentProposal">presentProposal</a>

Select whether a proposal for the opportunity has been presented to the account.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Presented Proposal</td></tr><tr><td>description</td><td>Select whether a proposal for the opportunity has been presented to the account.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>presentproposal</td></tr></table>

### <a href=#captureProposalFeedback name="captureProposalFeedback">captureProposalFeedback</a>

Choose whether the proposal feedback has been captured for the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Proposal Feedback Captured</td></tr><tr><td>description</td><td>Choose whether the proposal feedback has been captured for the opportunity.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>captureproposalfeedback</td></tr></table>

### <a href=#proposedSolution name="proposedSolution">proposedSolution</a>

Type notes about the proposed solution for the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Proposed Solution</td></tr><tr><td>description</td><td>Type notes about the proposed solution for the opportunity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>proposedsolution</td></tr></table>

### <a href=#pursuitDecision name="pursuitDecision">pursuitDecision</a>

Select whether the decision about pursuing the opportunity has been made.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Decide Go/No-Go</td></tr><tr><td>description</td><td>Select whether the decision about pursuing the opportunity has been made.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>pursuitdecision</td></tr></table>

### <a href=#qualificationComments name="qualificationComments">qualificationComments</a>

Type comments about the qualification or scoring of the lead.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Qualification Comments</td></tr><tr><td>description</td><td>Type comments about the qualification or scoring of the lead.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>qualificationcomments</td></tr></table>

### <a href=#quoteComments name="quoteComments">quoteComments</a>

Type comments about the quotes associated with the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote Comments</td></tr><tr><td>description</td><td>Type comments about the quotes associated with the opportunity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>quotecomments</td></tr></table>

### <a href=#sendThankYouNote name="sendThankYouNote">sendThankYouNote</a>

Select whether a thank you note has been sent to the account for considering the proposal.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Send Thank You Note</td></tr><tr><td>description</td><td>Select whether a thank you note has been sent to the account for considering the proposal.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sendthankyounote</td></tr></table>

### <a href=#scheduleFollowupProspect name="scheduleFollowupProspect">scheduleFollowupProspect</a>

Enter the date and time of the prospecting follow-up meeting with the lead.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Follow up (Prospect)</td></tr><tr><td>description</td><td>Enter the date and time of the prospecting follow-up meeting with the lead.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>schedulefollowup_prospect</td></tr></table>

### <a href=#scheduleFollowUpQualify name="scheduleFollowUpQualify">scheduleFollowUpQualify</a>

Enter the date and time of the qualifying follow-up meeting with the lead.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scheduled Follow up (Qualify)</td></tr><tr><td>description</td><td>Enter the date and time of the qualifying follow-up meeting with the lead.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>schedulefollowup_qualify</td></tr></table>

### <a href=#scheduleProposalMeeting name="scheduleProposalMeeting">scheduleProposalMeeting</a>

Enter the date and time of the proposal meeting for the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Schedule Proposal Meeting</td></tr><tr><td>description</td><td>Enter the date and time of the proposal meeting for the opportunity.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>scheduleproposalmeeting</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Shows whether the opportunity is open, won, or lost. Won and lost opportunities are read-only and can't be edited until they are reactivated.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the opportunity is open, won, or lost. Won and lost opportunities are read-only and can't be edited until they are reactivated.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Open</td><td>0</td></tr><tr><td>en</td><td>Won</td><td>1</td></tr><tr><td>en</td><td>Lost</td><td>2</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Select the opportunity's status.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the opportunity's status.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>In Progress</td><td>1</td><td>0</td></tr><tr><td>en</td><td>On Hold</td><td>2</td><td>0</td></tr><tr><td>en</td><td>Won</td><td>3</td><td>1</td></tr><tr><td>en</td><td>Canceled</td><td>4</td><td>2</td></tr><tr><td>en</td><td>Out-Sold</td><td>5</td><td>2</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#stepId name="stepId">stepId</a>

Shows the ID of the workflow step.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Step</td></tr><tr><td>description</td><td>Shows the ID of the workflow step.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stepid</td></tr></table>

### <a href=#stepName name="stepName">stepName</a>

Shows the current phase in the sales pipeline for the opportunity. This is updated by a workflow.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pipeline Phase</td></tr><tr><td>description</td><td>Shows the current phase in the sales pipeline for the opportunity. This is updated by a workflow.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stepname</td></tr></table>

### <a href=#timeLine name="timeLine">timeLine</a>

Select when the opportunity is likely to be closed.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Timeline</td></tr><tr><td>description</td><td>Select when the opportunity is likely to be closed.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timeline</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Immediate</td><td>0</td></tr><tr><td>en</td><td>This Quarter</td><td>1</td></tr><tr><td>en</td><td>Next Quarter</td><td>2</td></tr><tr><td>en</td><td>This Year</td><td>3</td></tr><tr><td>en</td><td>Not known</td><td>4</td></tr></table></td></tr></table>

### <a href=#timeLine_display name="timeLine_display">timeLine_display</a>

First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#totalAmount name="totalAmount">totalAmount</a>

Shows the total amount due, calculated as the sum of the products, discounts, freight, and taxes for the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Amount</td></tr><tr><td>description</td><td>Shows the total amount due, calculated as the sum of the products, discounts, freight, and taxes for the opportunity.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalamount</td></tr></table>

### <a href=#totalAmountBase name="totalAmountBase">totalAmountBase</a>

Value of the Total Amount in base currency.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Amount (Base)</td></tr><tr><td>description</td><td>Value of the Total Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalamount_base</td></tr></table>

### <a href=#totalAmountLessFreight name="totalAmountLessFreight">totalAmountLessFreight</a>

Shows the total product amount for the opportunity, minus any discounts. This value is added to freight and tax amounts in the calculation for the total amount of the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Pre-Freight Amount</td></tr><tr><td>description</td><td>Shows the total product amount for the opportunity, minus any discounts. This value is added to freight and tax amounts in the calculation for the total amount of the opportunity.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalamountlessfreight</td></tr></table>

### <a href=#totalAmountLessFreightBase name="totalAmountLessFreightBase">totalAmountLessFreightBase</a>

Value of the Total Pre-Freight Amount in base currency.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Pre-Freight Amount (Base)</td></tr><tr><td>description</td><td>Value of the Total Pre-Freight Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totalamountlessfreight_base</td></tr></table>

### <a href=#totalDiscountAmount name="totalDiscountAmount">totalDiscountAmount</a>

Shows the total discount amount, based on the discount price and rate entered on the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Discount Amount</td></tr><tr><td>description</td><td>Shows the total discount amount, based on the discount price and rate entered on the opportunity.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totaldiscountamount</td></tr></table>

### <a href=#totalDiscountAmountBase name="totalDiscountAmountBase">totalDiscountAmountBase</a>

Value of the Total Discount Amount in base currency.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Discount Amount (Base)</td></tr><tr><td>description</td><td>Value of the Total Discount Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totaldiscountamount_base</td></tr></table>

### <a href=#totalLineItemAmount name="totalLineItemAmount">totalLineItemAmount</a>

Shows the sum of all existing and write-in products included on the opportunity, based on the specified price list and quantities.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Detail Amount</td></tr><tr><td>description</td><td>Shows the sum of all existing and write-in products included on the opportunity, based on the specified price list and quantities.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totallineitemamount</td></tr></table>

### <a href=#totalLineItemAmountBase name="totalLineItemAmountBase">totalLineItemAmountBase</a>

Value of the Total Detail Amount in base currency.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Detail Amount (Base)</td></tr><tr><td>description</td><td>Value of the Total Detail Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totallineitemamount_base</td></tr></table>

### <a href=#totalLineItemDiscountAmount name="totalLineItemDiscountAmount">totalLineItemDiscountAmount</a>

Shows the total of the Manual Discount amounts specified on all products included in the opportunity. This value is reflected in the Total Detail Amount field on the opportunity and is added to any discount amount or rate specified on the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Line Item Discount Amount</td></tr><tr><td>description</td><td>Shows the total of the Manual Discount amounts specified on all products included in the opportunity. This value is reflected in the Total Detail Amount field on the opportunity and is added to any discount amount or rate specified on the opportunity.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totallineitemdiscountamount</td></tr></table>

### <a href=#totalLineItemDiscountAmountBase name="totalLineItemDiscountAmountBase">totalLineItemDiscountAmountBase</a>

Value of the Total Line Item Discount Amount in base currency.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Line Item Discount Amount (Base)</td></tr><tr><td>description</td><td>Value of the Total Line Item Discount Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totallineitemdiscountamount_base</td></tr></table>

### <a href=#totalTax name="totalTax">totalTax</a>

Shows the total of the Tax amounts specified on all products included in the opportunity, included in the Total Amount field calculation for the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Tax</td></tr><tr><td>description</td><td>Shows the total of the Tax amounts specified on all products included in the opportunity, included in the Total Amount field calculation for the opportunity.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totaltax</td></tr></table>

### <a href=#totalTaxBase name="totalTaxBase">totalTaxBase</a>

Value of the Total Tax in base currency.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Tax (Base)</td></tr><tr><td>description</td><td>Value of the Total Tax in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>totaltax_base</td></tr></table>

### <a href=#identifyCustomerContacts name="identifyCustomerContacts">identifyCustomerContacts</a>

Select whether the customer contacts for this opportunity have been identified.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Identify Customer Contacts</td></tr><tr><td>description</td><td>Select whether the customer contacts for this opportunity have been identified.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>identifycustomercontacts</td></tr></table>

### <a href=#identifyCompetitors name="identifyCompetitors">identifyCompetitors</a>

Select whether information about competitors is included.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Identify Competitors</td></tr><tr><td>description</td><td>Select whether information about competitors is included.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>identifycompetitors</td></tr></table>

### <a href=#identifyPursuitTeam name="identifyPursuitTeam">identifyPursuitTeam</a>

Choose whether you have recorded who will pursue the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Identify Sales Team</td></tr><tr><td>description</td><td>Choose whether you have recorded who will pursue the opportunity.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>identifypursuitteam</td></tr></table>

### <a href=#presentFinalProposal name="presentFinalProposal">presentFinalProposal</a>

Select whether the final proposal has been presented to the account.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Present Final Proposal</td></tr><tr><td>description</td><td>Select whether the final proposal has been presented to the account.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>presentfinalproposal</td></tr></table>

### <a href=#onHoldTime name="onHoldTime">onHoldTime</a>

Shows the duration in minutes for which the opportunity was on hold.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>On Hold Time (Minutes)</td></tr><tr><td>description</td><td>Shows the duration in minutes for which the opportunity was on hold.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>onholdtime</td></tr></table>

### <a href=#lastOnHoldTime name="lastOnHoldTime">lastOnHoldTime</a>

Contains the date time stamp of the last on hold time.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last On Hold Time</td></tr><tr><td>description</td><td>Contains the date time stamp of the last on hold time.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastonholdtime</td></tr></table>

### <a href=#SLAId name="SLAId">SLAId</a>

Choose the service level agreement (SLA) that you want to apply to the opportunity record.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA</td></tr><tr><td>description</td><td>Choose the service level agreement (SLA) that you want to apply to the opportunity record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slaid</td></tr></table>

### <a href=#SLAInvokedId name="SLAInvokedId">SLAInvokedId</a>

Last SLA that was applied to this opportunity. This field is for internal use only.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last SLA applied</td></tr><tr><td>description</td><td>Last SLA that was applied to this opportunity. This field is for internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slainvokedid</td></tr></table>

### <a href=#timeSpentByMeOnEmailAndMeetings name="timeSpentByMeOnEmailAndMeetings">timeSpentByMeOnEmailAndMeetings</a>

Total time spent for emails (read and write) and meetings by me in relation to the opportunity record.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Spent by me</td></tr><tr><td>description</td><td>Total time spent for emails (read and write) and meetings by me in relation to the opportunity record.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timespentbymeonemailandmeetings</td></tr></table>

### <a href=#originatingLeadId name="originatingLeadId">originatingLeadId</a>

Choose the lead that the opportunity was created from for reporting and analytics. The field is read-only after the opportunity is created and defaults to the correct lead when an opportunity is created from a converted lead.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Originating Lead</td></tr><tr><td>description</td><td>Choose the lead that the opportunity was created from for reporting and analytics. The field is read-only after the opportunity is created and defaults to the correct lead when an opportunity is created from a converted lead.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>originatingleadid</td></tr></table>

### <a href=#accountId name="accountId">accountId</a>

Unique identifier of the account with which the opportunity is associated.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the account with which the opportunity is associated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>accountid</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

Unique identifier of the contact associated with the opportunity.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>description</td><td>Unique identifier of the contact associated with the opportunity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>contactid</td></tr></table>

### <a href=#campaignId name="campaignId">campaignId</a>

Shows the campaign that the opportunity was created from. The ID is used for tracking the success of the campaign.  
First included in: <a href="../../../sales/Opportunity.md" target="_blank">sales/Opportunity</a>  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source Campaign</td></tr><tr><td>description</td><td>Shows the campaign that the opportunity was created from. The ID is used for tracking the success of the campaign.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>campaignid</td></tr></table>

### <a href=#costOfProperty name="costOfProperty">costOfProperty</a>

The price of the property for which customer is applying for the loan.  
First included in: banking/Opportunity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost of Property</td></tr><tr><td>description</td><td>The price of the property for which customer is applying for the loan.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_costofproperty</td></tr></table>

### <a href=#costOfPropertyBase name="costOfPropertyBase">costOfPropertyBase</a>

Value of the Cost of Property in base currency.  
First included in: banking/Opportunity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost of Property (Base)</td></tr><tr><td>description</td><td>Value of the Cost of Property in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_costofproperty_base</td></tr></table>

### <a href=#downPayment name="downPayment">downPayment</a>

The total down payment that customer has made against the car or property for which he is applying for the loan.  
First included in: banking/Opportunity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Down Payment</td></tr><tr><td>description</td><td>The total down payment that customer has made against the car or property for which he is applying for the loan.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_downpayment</td></tr></table>

### <a href=#downPaymentBase name="downPaymentBase">downPaymentBase</a>

Value of the Down Payment in base currency.  
First included in: banking/Opportunity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Down Payment (Base)</td></tr><tr><td>description</td><td>Value of the Down Payment in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_downpayment_base</td></tr></table>

### <a href=#interestRate name="interestRate">interestRate</a>

The rate of interest applicable to the product. The applicable rate must be fetched from the product catalog based on the requested amount.  
First included in: banking/Opportunity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interest Rate</td></tr><tr><td>description</td><td>The rate of interest applicable to the product. The applicable rate must be fetched from the product catalog based on the requested amount.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_interestrate</td></tr></table>

### <a href=#preferredFollowUpTime name="preferredFollowUpTime">preferredFollowUpTime</a>

Convenient time for the customer to be contacted.  
First included in: banking/Opportunity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Preferred Follow-up Time</td></tr><tr><td>description</td><td>Convenient time for the customer to be contacted.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msfsi_preferredfollowuptime</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#preferredFollowUpTime_display name="preferredFollowUpTime_display">preferredFollowUpTime_display</a>

First included in: banking/Opportunity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#productId name="productId">productId</a>

The product that the customer is applying for.  
First included in: banking/Opportunity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product</td></tr><tr><td>description</td><td>The product that the customer is applying for.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msfsi_productid</td></tr></table>

### <a href=#purposeOfLoan name="purposeOfLoan">purposeOfLoan</a>

The reason or purpose for which customer is applying for the loan.  
First included in: banking/Opportunity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purpose of Loan</td></tr><tr><td>description</td><td>The reason or purpose for which customer is applying for the loan.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_purposeofloan</td></tr></table>

### <a href=#requestedAmount name="requestedAmount">requestedAmount</a>

The amount of the product that customer is applying for such as the loan amount or card limit.  
First included in: banking/Opportunity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requested Amount</td></tr><tr><td>description</td><td>The amount of the product that customer is applying for such as the loan amount or card limit.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_requestedamount</td></tr></table>

### <a href=#requestedAmountBase name="requestedAmountBase">requestedAmountBase</a>

Value of the Requested Amount in base currency.  
First included in: banking/Opportunity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requested Amount (Base)</td></tr><tr><td>description</td><td>Value of the Requested Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_requestedamount_base</td></tr></table>

### <a href=#termOfLoan name="termOfLoan">termOfLoan</a>

The number of months that customer is requesting as term of the loan.  
First included in: banking/Opportunity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Term of Loan</td></tr><tr><td>description</td><td>The number of months that customer is requesting as term of the loan.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_termofloan</td></tr></table>
