---
title: FinancialProduct - Common Data Model | Microsoft Docs
description: The record of the different products that the customer holds with the bank.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Financial Product

The record of the different products that the customer holds with the bank.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/financialServices/banking/FinancialProduct.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/financialServices/banking/FinancialProduct  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[ownerId](#ownerId)|Owner Id|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[exchangeRate](#exchangeRate)|Exchange rate for the currency associated with the entity with respect to the base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[availableBalance](#availableBalance)|The balance of the product at the time that the information is imported to D365 or when the information is retrieved in real-time form the backend system (such as the account balance). This is the amo|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[availableBalanceBase](#availableBalanceBase)|Value of the Available Balance in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[averageBalance](#averageBalance)|The average balance in the account calculated over a chosen period of time by the bank.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[averageBalanceBase](#averageBalanceBase)|Value of the Average Balance in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[balanceAtMaturity](#balanceAtMaturity)|The total amount that will be available in the account at the time of deposit maturity, which would include the principal deposit amount and the interest earned.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[balanceAtMaturityBase](#balanceAtMaturityBase)|Value of the Balance at Maturity in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[blockedAmount](#blockedAmount)|The amount of the account’s balance that has been blocked/reserved by the bank for a specific purpose or a as a security measure.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[blockedAmountBase](#blockedAmountBase)|Value of the Blocked Amount in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[bookBalance](#bookBalance)|The balance available on the account (excluding the cheques pending clearing, deposits in transit, or any other deductions on the account).|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[bookBalanceBase](#bookBalanceBase)|Value of the Book Balance in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[branchId](#branchId)|The branch at which this product was originated.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[capitalArrears](#capitalArrears)|Total overdue principal amount on the loan.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[capitalArrearsBase](#capitalArrearsBase)|Value of the Capital Arrears in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[collectionRisk](#collectionRisk)|The risk of collection/repayment by the customer.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[collectionRisk_display](#collectionRisk_display)||<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[customerIdType](#customerIdType)|The type of customer, either Account or Contact.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[customerId](#customerId)|The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[daysPastDue](#daysPastDue)|The number of days that the customer has been in overdue status for this loan account.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[debtType](#debtType)|Debt type of the loan.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[debtType_display](#debtType_display)||<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[delinquencyStatus](#delinquencyStatus)|Indication of whether the customer’s loan is delinquent or not (i.e. whether any payments are overdue or not).|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[delinquencyStatus_display](#delinquencyStatus_display)||<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[disbursedAmount](#disbursedAmount)|The amount of loan that has been disbursed to the customer so far.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[disbursedAmountBase](#disbursedAmountBase)|Value of the Disbursed Amount in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[disbursementDate](#disbursementDate)|The date on which the loan was disbursed to the customer’s account.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[financialProductId](#financialProductId)|Unique identifier for entity instances|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[initialDeposit](#initialDeposit)|The amount that was initially deposited by the customer in to the account when the account was first opened. This information is part of the Account Opening KYC.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[initialDepositBase](#initialDepositBase)|Value of the Initial Deposit in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[initialDepositSource](#initialDepositSource)|The source of funds that was initially deposited in to the account. This information is part of the Account Opening KYC.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[installmentAmount](#installmentAmount)|The equal installment amounts that the customer pays back to the bank towards the loan on a monthly basis (EMI).|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[installmentAmountBase](#installmentAmountBase)|Value of the Installment Amount in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[interestAmount](#interestAmount)|The total amount of interest to be paid by the customer on the amount borrowed from the bank.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[interestAmountBase](#interestAmountBase)|Value of the Interest Amount in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[interestArrears](#interestArrears)|Total overdue interest amount on the loan.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[interestArrearsBase](#interestArrearsBase)|Value of the Interest Arrears in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[interestRate](#interestRate)|The rate of interest applied to the loan, based on which the customer will pay interest on the loan for the duration of the loan.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[isSyndicated](#isSyndicated)|Flag indicating the loan is syndicated or not|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[jointType](#jointType)|Indication of the account’s operation type as single or joint.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[jointType_display](#jointType_display)||<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[lastPaymentAmount](#lastPaymentAmount)|The amount that was paid by the customer towards the loan in the last repayment.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[lastPaymentAmountBase](#lastPaymentAmountBase)|Value of the Last Payment Amount in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[lastPaymentDate](#lastPaymentDate)|The date on which the last repayment towards the loan was made by the customer.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[limitId](#limitId)|The Limit of the customer or account|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[loanMaturityDate](#loanMaturityDate)|The date on which the last repayment towards the loan will be made, and the customer’s full borrowing will be paid back.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[loanStartDate](#loanStartDate)|The date on which the first repayment on the loan is made.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[loanType](#loanType)|The type of loan that the customer has availed from the bank such as a new loan or a top up.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[loanType_display](#loanType_display)||<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[maturityDate](#maturityDate)|The date on which the fixed deposit will reach maturity and customer can withdraw from the account.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[maturityInstructionsDetails](#maturityInstructionsDetails)|The instructions given by the customer to be taken on the account upon maturity such as transfer of interest to another account, or transfer of principal and interest amount to another account, or rol|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[modeOfPayment](#modeOfPayment)|The method that customer is making repayments towards the loan.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[modeOfPayment_display](#modeOfPayment_display)||<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[nextPaymentAmount](#nextPaymentAmount)|The amount that needs to be paid by the customer towards the loan in the next installment.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[nextPaymentAmountBase](#nextPaymentAmountBase)|Value of the Next Payment Amount in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[nextPaymentDate](#nextPaymentDate)|The date on which the next repayment towards the loan is due.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[number](#number)|The name of the custom entity.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[numberOfDeferralsMade](#numberOfDeferralsMade)|Total number of installment deferrals made by the customer (i.e. number of times customer has taken a loan repayment holiday from the bank).|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[numberOfInstallmentsPaid](#numberOfInstallmentsPaid)|Total number of installments that have been paid back by the customer so far.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[openingDate](#openingDate)|The date on which the account was opened.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[outstandingPrincipalAmount](#outstandingPrincipalAmount)|The total amount remaining to be paid back by the customer towards the loan’s principal amount.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[outstandingPrincipalAmountBase](#outstandingPrincipalAmountBase)|Value of the Outstanding Principal Amount in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[outstandingTotalAmount](#outstandingTotalAmount)|The total amount remaining to be paid back by the customer towards the loan’s principal amount and the interest amount.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[outstandingTotalAmountBase](#outstandingTotalAmountBase)|Value of the Outstanding Total Amount in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[overdraftLimit](#overdraftLimit)|The overdraft limit given by the bank to the customer on this account. This is the amount that customer can withdraw from the account, when the account reaches zero balance.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[overdraftLimitBase](#overdraftLimitBase)|Value of the Overdraft Limit in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[overdraftRate](#overdraftRate)|The interest rate that will be applied to the customer for repayment, if the account falls into overdraft.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[overdueDate](#overdueDate)|The date on which the repayment was missed and the loan became overdue.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[overdueInstallmentAmount](#overdueInstallmentAmount)|The total amount of repayments towards the loan which have been missed by the customer and are overdue.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[overdueInstallmentAmountBase](#overdueInstallmentAmountBase)|Value of the Overdue Installment Amount in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[principalAmount](#principalAmount)|The amount that the customer has borrowed from the bank.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[principalAmountBase](#principalAmountBase)|Value of the Principal Amount in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[productFamilyId](#productFamilyId)|Lookup to product family from D365|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[productId](#productId)|Name of the product held by the customer such as Savings Account or Car Loan.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[projectedInterestAmount](#projectedInterestAmount)|The amount of interested expected to be earned on the account based on the interest rate.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[projectedInterestAmountBase](#projectedInterestAmountBase)|Value of the Projected Interest Amount in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[purposeOfLoan](#purposeOfLoan)|The customer’s purpose in borrowing from the bank such as holidays or home renovation.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[rate](#rate)|The rate of interest applied to the deposit account based on which interest will be earned during the defined period/term.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[sourceOfFunds](#sourceOfFunds)|The source of funds that will be deposited into the account throughout the account’s lifecycle. This information is part of the Account Opening KYC.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[term](#term)|The number of months that the deposit account has been set up for.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[totalArrear](#totalArrear)|Total overdue amount on the loan.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[totalArrearBase](#totalArrearBase)|Value of the Total Arrear in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[totalInterestPaid](#totalInterestPaid)|Total amount of payments made towards interest of the loan to date.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[totalInterestPaidBase](#totalInterestPaidBase)|Value of the Total Interest Paid in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[unclearedBalance](#unclearedBalance)|The amount of funds yes to be credited to the account, pending to be cleared, (such as cheques favouring the account).|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[unclearedBalanceBase](#unclearedBalanceBase)|Value of the Uncleared Balance in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[unsecuredAmount](#unsecuredAmount)|Total amount of the loan that is not secured.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[unsecuredAmountBase](#unsecuredAmountBase)|Value of the Unsecured Amount in base currency.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[deprecatedStageId](#deprecatedStageId)|Contains the id of the stage where the entity is located.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[stateCode](#stateCode)|Status of the Financial Product|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[stateCode_display](#stateCode_display)||<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[statusCode](#statusCode)|Reason for the status of the Financial Product|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[statusCode_display](#statusCode_display)||<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Unique identifier of the currency associated with the entity.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|
|[deprecatedTraversedPath](#deprecatedTraversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="FinancialProduct.md" target="_blank">banking/FinancialProduct</a>|

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#ownerIdType name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr></table>

### <a href=#ownerId name="ownerId">ownerId</a>

Owner Id  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>ownerid</td></tr></table>

### <a href=#owningBusinessUnit name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr></table>

### <a href=#owningUser name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr></table>

### <a href=#owningTeam name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Exchange rate for the currency associated with the entity with respect to the base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Exchange rate for the currency associated with the entity with respect to the base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#availableBalance name="availableBalance">availableBalance</a>

The balance of the product at the time that the information is imported to D365 or when the information is retrieved in real-time form the backend system (such as the account balance). This is the amo  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Available Balance</td></tr><tr><td>description</td><td>The balance of the product at the time that the information is imported to D365 or when the information is retrieved in real-time form the backend system (such as the account balance). This is the amo</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_availablebalance</td></tr></table>

### <a href=#availableBalanceBase name="availableBalanceBase">availableBalanceBase</a>

Value of the Available Balance in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Available Balance (Base)</td></tr><tr><td>description</td><td>Value of the Available Balance in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_availablebalance_base</td></tr></table>

### <a href=#averageBalance name="averageBalance">averageBalance</a>

The average balance in the account calculated over a chosen period of time by the bank.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Average Balance</td></tr><tr><td>description</td><td>The average balance in the account calculated over a chosen period of time by the bank.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_averagebalance</td></tr></table>

### <a href=#averageBalanceBase name="averageBalanceBase">averageBalanceBase</a>

Value of the Average Balance in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Average Balance (Base)</td></tr><tr><td>description</td><td>Value of the Average Balance in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_averagebalance_base</td></tr></table>

### <a href=#balanceAtMaturity name="balanceAtMaturity">balanceAtMaturity</a>

The total amount that will be available in the account at the time of deposit maturity, which would include the principal deposit amount and the interest earned.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Balance at Maturity</td></tr><tr><td>description</td><td>The total amount that will be available in the account at the time of deposit maturity, which would include the principal deposit amount and the interest earned.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_balanceatmaturity</td></tr></table>

### <a href=#balanceAtMaturityBase name="balanceAtMaturityBase">balanceAtMaturityBase</a>

Value of the Balance at Maturity in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Balance at Maturity (Base)</td></tr><tr><td>description</td><td>Value of the Balance at Maturity in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_balanceatmaturity_base</td></tr></table>

### <a href=#blockedAmount name="blockedAmount">blockedAmount</a>

The amount of the account’s balance that has been blocked/reserved by the bank for a specific purpose or a as a security measure.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Blocked Amount</td></tr><tr><td>description</td><td>The amount of the account’s balance that has been blocked/reserved by the bank for a specific purpose or a as a security measure.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_blockedamount</td></tr></table>

### <a href=#blockedAmountBase name="blockedAmountBase">blockedAmountBase</a>

Value of the Blocked Amount in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Blocked Amount (Base)</td></tr><tr><td>description</td><td>Value of the Blocked Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_blockedamount_base</td></tr></table>

### <a href=#bookBalance name="bookBalance">bookBalance</a>

The balance available on the account (excluding the cheques pending clearing, deposits in transit, or any other deductions on the account).  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Book Balance</td></tr><tr><td>description</td><td>The balance available on the account (excluding the cheques pending clearing, deposits in transit, or any other deductions on the account).</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_bookbalance</td></tr></table>

### <a href=#bookBalanceBase name="bookBalanceBase">bookBalanceBase</a>

Value of the Book Balance in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Book Balance (Base)</td></tr><tr><td>description</td><td>Value of the Book Balance in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_bookbalance_base</td></tr></table>

### <a href=#branchId name="branchId">branchId</a>

The branch at which this product was originated.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Branch</td></tr><tr><td>description</td><td>The branch at which this product was originated.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msfsi_branchid</td></tr></table>

### <a href=#capitalArrears name="capitalArrears">capitalArrears</a>

Total overdue principal amount on the loan.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Capital Arrears</td></tr><tr><td>description</td><td>Total overdue principal amount on the loan.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_capitalarrears</td></tr></table>

### <a href=#capitalArrearsBase name="capitalArrearsBase">capitalArrearsBase</a>

Value of the Capital Arrears in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Capital Arrears (Base)</td></tr><tr><td>description</td><td>Value of the Capital Arrears in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_capitalarrears_base</td></tr></table>

### <a href=#collectionRisk name="collectionRisk">collectionRisk</a>

The risk of collection/repayment by the customer.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Collection Risk</td></tr><tr><td>description</td><td>The risk of collection/repayment by the customer.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msfsi_collectionrisk</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#collectionRisk_display name="collectionRisk_display">collectionRisk_display</a>

First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#customerIdType name="customerIdType">customerIdType</a>

The type of customer, either Account or Contact.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer Type</td></tr><tr><td>description</td><td>The type of customer, either Account or Contact.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>sourceName</td><td>customeridtype</td></tr></table>

### <a href=#customerId name="customerId">customerId</a>

The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer</td></tr><tr><td>description</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customerid</td></tr></table>

### <a href=#daysPastDue name="daysPastDue">daysPastDue</a>

The number of days that the customer has been in overdue status for this loan account.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Days Past Due</td></tr><tr><td>description</td><td>The number of days that the customer has been in overdue status for this loan account.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_dayspastdue</td></tr></table>

### <a href=#debtType name="debtType">debtType</a>

Debt type of the loan.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Debt Type</td></tr><tr><td>description</td><td>Debt type of the loan.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msfsi_debttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#debtType_display name="debtType_display">debtType_display</a>

First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#delinquencyStatus name="delinquencyStatus">delinquencyStatus</a>

Indication of whether the customer’s loan is delinquent or not (i.e. whether any payments are overdue or not).  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delinquency Status</td></tr><tr><td>description</td><td>Indication of whether the customer’s loan is delinquent or not (i.e. whether any payments are overdue or not).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msfsi_delinquencystatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#delinquencyStatus_display name="delinquencyStatus_display">delinquencyStatus_display</a>

First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#disbursedAmount name="disbursedAmount">disbursedAmount</a>

The amount of loan that has been disbursed to the customer so far.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disbursed Amount</td></tr><tr><td>description</td><td>The amount of loan that has been disbursed to the customer so far.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_disbursedamount</td></tr></table>

### <a href=#disbursedAmountBase name="disbursedAmountBase">disbursedAmountBase</a>

Value of the Disbursed Amount in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disbursed Amount (Base)</td></tr><tr><td>description</td><td>Value of the Disbursed Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_disbursedamount_base</td></tr></table>

### <a href=#disbursementDate name="disbursementDate">disbursementDate</a>

The date on which the loan was disbursed to the customer’s account.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disbursement Date</td></tr><tr><td>description</td><td>The date on which the loan was disbursed to the customer’s account.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msfsi_disbursementdate</td></tr></table>

### <a href=#financialProductId name="financialProductId">financialProductId</a>

Unique identifier for entity instances  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Financial Product</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msfsi_financialproductid</td></tr></table>

### <a href=#initialDeposit name="initialDeposit">initialDeposit</a>

The amount that was initially deposited by the customer in to the account when the account was first opened. This information is part of the Account Opening KYC.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Initial Deposit</td></tr><tr><td>description</td><td>The amount that was initially deposited by the customer in to the account when the account was first opened. This information is part of the Account Opening KYC.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_initialdeposit</td></tr></table>

### <a href=#initialDepositBase name="initialDepositBase">initialDepositBase</a>

Value of the Initial Deposit in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Initial Deposit (Base)</td></tr><tr><td>description</td><td>Value of the Initial Deposit in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_initialdeposit_base</td></tr></table>

### <a href=#initialDepositSource name="initialDepositSource">initialDepositSource</a>

The source of funds that was initially deposited in to the account. This information is part of the Account Opening KYC.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Initial Deposit Source</td></tr><tr><td>description</td><td>The source of funds that was initially deposited in to the account. This information is part of the Account Opening KYC.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_initialdepositsource</td></tr></table>

### <a href=#installmentAmount name="installmentAmount">installmentAmount</a>

The equal installment amounts that the customer pays back to the bank towards the loan on a monthly basis (EMI).  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Installment Amount</td></tr><tr><td>description</td><td>The equal installment amounts that the customer pays back to the bank towards the loan on a monthly basis (EMI).</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_installmentamount</td></tr></table>

### <a href=#installmentAmountBase name="installmentAmountBase">installmentAmountBase</a>

Value of the Installment Amount in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Installment Amount (Base)</td></tr><tr><td>description</td><td>Value of the Installment Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_installmentamount_base</td></tr></table>

### <a href=#interestAmount name="interestAmount">interestAmount</a>

The total amount of interest to be paid by the customer on the amount borrowed from the bank.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interest Amount</td></tr><tr><td>description</td><td>The total amount of interest to be paid by the customer on the amount borrowed from the bank.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_interestamount</td></tr></table>

### <a href=#interestAmountBase name="interestAmountBase">interestAmountBase</a>

Value of the Interest Amount in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interest Amount (Base)</td></tr><tr><td>description</td><td>Value of the Interest Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_interestamount_base</td></tr></table>

### <a href=#interestArrears name="interestArrears">interestArrears</a>

Total overdue interest amount on the loan.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interest Arrears</td></tr><tr><td>description</td><td>Total overdue interest amount on the loan.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_interestarrears</td></tr></table>

### <a href=#interestArrearsBase name="interestArrearsBase">interestArrearsBase</a>

Value of the Interest Arrears in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interest Arrears (Base)</td></tr><tr><td>description</td><td>Value of the Interest Arrears in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_interestarrears_base</td></tr></table>

### <a href=#interestRate name="interestRate">interestRate</a>

The rate of interest applied to the loan, based on which the customer will pay interest on the loan for the duration of the loan.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interest Rate</td></tr><tr><td>description</td><td>The rate of interest applied to the loan, based on which the customer will pay interest on the loan for the duration of the loan.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_interestrate</td></tr></table>

### <a href=#isSyndicated name="isSyndicated">isSyndicated</a>

Flag indicating the loan is syndicated or not  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Syndicated</td></tr><tr><td>description</td><td>Flag indicating the loan is syndicated or not</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>msfsi_issyndicated</td></tr></table>

### <a href=#jointType name="jointType">jointType</a>

Indication of the account’s operation type as single or joint.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Joint Type</td></tr><tr><td>description</td><td>Indication of the account’s operation type as single or joint.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msfsi_jointtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#jointType_display name="jointType_display">jointType_display</a>

First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#lastPaymentAmount name="lastPaymentAmount">lastPaymentAmount</a>

The amount that was paid by the customer towards the loan in the last repayment.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Payment Amount</td></tr><tr><td>description</td><td>The amount that was paid by the customer towards the loan in the last repayment.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_lastpaymentamount</td></tr></table>

### <a href=#lastPaymentAmountBase name="lastPaymentAmountBase">lastPaymentAmountBase</a>

Value of the Last Payment Amount in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Payment Amount (Base)</td></tr><tr><td>description</td><td>Value of the Last Payment Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_lastpaymentamount_base</td></tr></table>

### <a href=#lastPaymentDate name="lastPaymentDate">lastPaymentDate</a>

The date on which the last repayment towards the loan was made by the customer.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Payment Date</td></tr><tr><td>description</td><td>The date on which the last repayment towards the loan was made by the customer.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msfsi_lastpaymentdate</td></tr></table>

### <a href=#limitId name="limitId">limitId</a>

The Limit of the customer or account  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Limit</td></tr><tr><td>description</td><td>The Limit of the customer or account</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msfsi_limitid</td></tr></table>

### <a href=#loanMaturityDate name="loanMaturityDate">loanMaturityDate</a>

The date on which the last repayment towards the loan will be made, and the customer’s full borrowing will be paid back.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Loan Maturity Date</td></tr><tr><td>description</td><td>The date on which the last repayment towards the loan will be made, and the customer’s full borrowing will be paid back.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msfsi_loanmaturitydate</td></tr></table>

### <a href=#loanStartDate name="loanStartDate">loanStartDate</a>

The date on which the first repayment on the loan is made.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Loan Start Date</td></tr><tr><td>description</td><td>The date on which the first repayment on the loan is made.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msfsi_loanstartdate</td></tr></table>

### <a href=#loanType name="loanType">loanType</a>

The type of loan that the customer has availed from the bank such as a new loan or a top up.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Loan Type</td></tr><tr><td>description</td><td>The type of loan that the customer has availed from the bank such as a new loan or a top up.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msfsi_loantype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#loanType_display name="loanType_display">loanType_display</a>

First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#maturityDate name="maturityDate">maturityDate</a>

The date on which the fixed deposit will reach maturity and customer can withdraw from the account.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maturity Date</td></tr><tr><td>description</td><td>The date on which the fixed deposit will reach maturity and customer can withdraw from the account.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msfsi_maturitydate</td></tr></table>

### <a href=#maturityInstructionsDetails name="maturityInstructionsDetails">maturityInstructionsDetails</a>

The instructions given by the customer to be taken on the account upon maturity such as transfer of interest to another account, or transfer of principal and interest amount to another account, or rol  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maturity Instructions Details</td></tr><tr><td>description</td><td>The instructions given by the customer to be taken on the account upon maturity such as transfer of interest to another account, or transfer of principal and interest amount to another account, or rol</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_maturityinstructionsdetails</td></tr></table>

### <a href=#modeOfPayment name="modeOfPayment">modeOfPayment</a>

The method that customer is making repayments towards the loan.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mode of Payment</td></tr><tr><td>description</td><td>The method that customer is making repayments towards the loan.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>msfsi_modeofpayment</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr></tr><tr></tr><tr></tr><tr></tr></table></td></tr></table>

### <a href=#modeOfPayment_display name="modeOfPayment_display">modeOfPayment_display</a>

First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#nextPaymentAmount name="nextPaymentAmount">nextPaymentAmount</a>

The amount that needs to be paid by the customer towards the loan in the next installment.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Next Payment Amount</td></tr><tr><td>description</td><td>The amount that needs to be paid by the customer towards the loan in the next installment.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_nextpaymentamount</td></tr></table>

### <a href=#nextPaymentAmountBase name="nextPaymentAmountBase">nextPaymentAmountBase</a>

Value of the Next Payment Amount in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Next Payment Amount (Base)</td></tr><tr><td>description</td><td>Value of the Next Payment Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_nextpaymentamount_base</td></tr></table>

### <a href=#nextPaymentDate name="nextPaymentDate">nextPaymentDate</a>

The date on which the next repayment towards the loan is due.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Next Payment Date</td></tr><tr><td>description</td><td>The date on which the next repayment towards the loan is due.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msfsi_nextpaymentdate</td></tr></table>

### <a href=#number name="number">number</a>

The name of the custom entity.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number</td></tr><tr><td>description</td><td>The name of the custom entity.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_number</td></tr></table>

### <a href=#numberOfDeferralsMade name="numberOfDeferralsMade">numberOfDeferralsMade</a>

Total number of installment deferrals made by the customer (i.e. number of times customer has taken a loan repayment holiday from the bank).  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of Deferrals Made</td></tr><tr><td>description</td><td>Total number of installment deferrals made by the customer (i.e. number of times customer has taken a loan repayment holiday from the bank).</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_numberofdeferralsmade</td></tr></table>

### <a href=#numberOfInstallmentsPaid name="numberOfInstallmentsPaid">numberOfInstallmentsPaid</a>

Total number of installments that have been paid back by the customer so far.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of Installments Paid</td></tr><tr><td>description</td><td>Total number of installments that have been paid back by the customer so far.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_numberofinstallmentspaid</td></tr></table>

### <a href=#openingDate name="openingDate">openingDate</a>

The date on which the account was opened.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Opening Date</td></tr><tr><td>description</td><td>The date on which the account was opened.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msfsi_openingdate</td></tr></table>

### <a href=#outstandingPrincipalAmount name="outstandingPrincipalAmount">outstandingPrincipalAmount</a>

The total amount remaining to be paid back by the customer towards the loan’s principal amount.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Outstanding Principal Amount</td></tr><tr><td>description</td><td>The total amount remaining to be paid back by the customer towards the loan’s principal amount.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_outstandingprincipalamount</td></tr></table>

### <a href=#outstandingPrincipalAmountBase name="outstandingPrincipalAmountBase">outstandingPrincipalAmountBase</a>

Value of the Outstanding Principal Amount in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Outstanding Principal Amount (Base)</td></tr><tr><td>description</td><td>Value of the Outstanding Principal Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_outstandingprincipalamount_base</td></tr></table>

### <a href=#outstandingTotalAmount name="outstandingTotalAmount">outstandingTotalAmount</a>

The total amount remaining to be paid back by the customer towards the loan’s principal amount and the interest amount.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Outstanding Total Amount</td></tr><tr><td>description</td><td>The total amount remaining to be paid back by the customer towards the loan’s principal amount and the interest amount.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_outstandingtotalamount</td></tr></table>

### <a href=#outstandingTotalAmountBase name="outstandingTotalAmountBase">outstandingTotalAmountBase</a>

Value of the Outstanding Total Amount in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Outstanding Total Amount (Base)</td></tr><tr><td>description</td><td>Value of the Outstanding Total Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_outstandingtotalamount_base</td></tr></table>

### <a href=#overdraftLimit name="overdraftLimit">overdraftLimit</a>

The overdraft limit given by the bank to the customer on this account. This is the amount that customer can withdraw from the account, when the account reaches zero balance.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overdraft Limit</td></tr><tr><td>description</td><td>The overdraft limit given by the bank to the customer on this account. This is the amount that customer can withdraw from the account, when the account reaches zero balance.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_overdraftlimit</td></tr></table>

### <a href=#overdraftLimitBase name="overdraftLimitBase">overdraftLimitBase</a>

Value of the Overdraft Limit in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overdraft Limit (Base)</td></tr><tr><td>description</td><td>Value of the Overdraft Limit in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_overdraftlimit_base</td></tr></table>

### <a href=#overdraftRate name="overdraftRate">overdraftRate</a>

The interest rate that will be applied to the customer for repayment, if the account falls into overdraft.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overdraft Rate</td></tr><tr><td>description</td><td>The interest rate that will be applied to the customer for repayment, if the account falls into overdraft.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_overdraftrate</td></tr></table>

### <a href=#overdueDate name="overdueDate">overdueDate</a>

The date on which the repayment was missed and the loan became overdue.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overdue Date</td></tr><tr><td>description</td><td>The date on which the repayment was missed and the loan became overdue.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>msfsi_overduedate</td></tr></table>

### <a href=#overdueInstallmentAmount name="overdueInstallmentAmount">overdueInstallmentAmount</a>

The total amount of repayments towards the loan which have been missed by the customer and are overdue.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overdue Installment Amount</td></tr><tr><td>description</td><td>The total amount of repayments towards the loan which have been missed by the customer and are overdue.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_overdueinstallmentamount</td></tr></table>

### <a href=#overdueInstallmentAmountBase name="overdueInstallmentAmountBase">overdueInstallmentAmountBase</a>

Value of the Overdue Installment Amount in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overdue Installment Amount (Base)</td></tr><tr><td>description</td><td>Value of the Overdue Installment Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_overdueinstallmentamount_base</td></tr></table>

### <a href=#principalAmount name="principalAmount">principalAmount</a>

The amount that the customer has borrowed from the bank.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Principal Amount</td></tr><tr><td>description</td><td>The amount that the customer has borrowed from the bank.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_principalamount</td></tr></table>

### <a href=#principalAmountBase name="principalAmountBase">principalAmountBase</a>

Value of the Principal Amount in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Principal Amount (Base)</td></tr><tr><td>description</td><td>Value of the Principal Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_principalamount_base</td></tr></table>

### <a href=#productFamilyId name="productFamilyId">productFamilyId</a>

Lookup to product family from D365  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product Family</td></tr><tr><td>description</td><td>Lookup to product family from D365</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msfsi_productfamilyid</td></tr></table>

### <a href=#productId name="productId">productId</a>

Name of the product held by the customer such as Savings Account or Car Loan.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product</td></tr><tr><td>description</td><td>Name of the product held by the customer such as Savings Account or Car Loan.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>msfsi_productid</td></tr></table>

### <a href=#projectedInterestAmount name="projectedInterestAmount">projectedInterestAmount</a>

The amount of interested expected to be earned on the account based on the interest rate.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Projected Interest Amount</td></tr><tr><td>description</td><td>The amount of interested expected to be earned on the account based on the interest rate.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_projectedinterestamount</td></tr></table>

### <a href=#projectedInterestAmountBase name="projectedInterestAmountBase">projectedInterestAmountBase</a>

Value of the Projected Interest Amount in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Projected Interest Amount (Base)</td></tr><tr><td>description</td><td>Value of the Projected Interest Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_projectedinterestamount_base</td></tr></table>

### <a href=#purposeOfLoan name="purposeOfLoan">purposeOfLoan</a>

The customer’s purpose in borrowing from the bank such as holidays or home renovation.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purpose of Loan</td></tr><tr><td>description</td><td>The customer’s purpose in borrowing from the bank such as holidays or home renovation.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_purposeofloan</td></tr></table>

### <a href=#rate name="rate">rate</a>

The rate of interest applied to the deposit account based on which interest will be earned during the defined period/term.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rate</td></tr><tr><td>description</td><td>The rate of interest applied to the deposit account based on which interest will be earned during the defined period/term.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_rate</td></tr></table>

### <a href=#sourceOfFunds name="sourceOfFunds">sourceOfFunds</a>

The source of funds that will be deposited into the account throughout the account’s lifecycle. This information is part of the Account Opening KYC.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source of Funds</td></tr><tr><td>description</td><td>The source of funds that will be deposited into the account throughout the account’s lifecycle. This information is part of the Account Opening KYC.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>msfsi_sourceoffunds</td></tr></table>

### <a href=#term name="term">term</a>

The number of months that the deposit account has been set up for.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Term</td></tr><tr><td>description</td><td>The number of months that the deposit account has been set up for.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_term</td></tr></table>

### <a href=#totalArrear name="totalArrear">totalArrear</a>

Total overdue amount on the loan.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Arrear</td></tr><tr><td>description</td><td>Total overdue amount on the loan.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_totalarrear</td></tr></table>

### <a href=#totalArrearBase name="totalArrearBase">totalArrearBase</a>

Value of the Total Arrear in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Arrear (Base)</td></tr><tr><td>description</td><td>Value of the Total Arrear in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_totalarrear_base</td></tr></table>

### <a href=#totalInterestPaid name="totalInterestPaid">totalInterestPaid</a>

Total amount of payments made towards interest of the loan to date.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Interest Paid</td></tr><tr><td>description</td><td>Total amount of payments made towards interest of the loan to date.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_totalinterestpaid</td></tr></table>

### <a href=#totalInterestPaidBase name="totalInterestPaidBase">totalInterestPaidBase</a>

Value of the Total Interest Paid in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total Interest Paid (Base)</td></tr><tr><td>description</td><td>Value of the Total Interest Paid in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_totalinterestpaid_base</td></tr></table>

### <a href=#unclearedBalance name="unclearedBalance">unclearedBalance</a>

The amount of funds yes to be credited to the account, pending to be cleared, (such as cheques favouring the account).  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Uncleared Balance</td></tr><tr><td>description</td><td>The amount of funds yes to be credited to the account, pending to be cleared, (such as cheques favouring the account).</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_unclearedbalance</td></tr></table>

### <a href=#unclearedBalanceBase name="unclearedBalanceBase">unclearedBalanceBase</a>

Value of the Uncleared Balance in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Uncleared Balance (Base)</td></tr><tr><td>description</td><td>Value of the Uncleared Balance in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_unclearedbalance_base</td></tr></table>

### <a href=#unsecuredAmount name="unsecuredAmount">unsecuredAmount</a>

Total amount of the loan that is not secured.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unsecured Amount</td></tr><tr><td>description</td><td>Total amount of the loan that is not secured.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>msfsi_unsecuredamount</td></tr></table>

### <a href=#unsecuredAmountBase name="unsecuredAmountBase">unsecuredAmountBase</a>

Value of the Unsecured Amount in base currency.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unsecured Amount (Base)</td></tr><tr><td>description</td><td>Value of the Unsecured Amount in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>sourceName</td><td>msfsi_unsecuredamount_base</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#deprecatedStageId name="deprecatedStageId">deprecatedStageId</a>

Contains the id of the stage where the entity is located.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>(Deprecated) Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Financial Product  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Financial Product</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Financial Product  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Financial Product</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Unique identifier of the currency associated with the entity.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the currency associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#deprecatedTraversedPath name="deprecatedTraversedPath">deprecatedTraversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: banking/FinancialProduct (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>(Deprecated) Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>
