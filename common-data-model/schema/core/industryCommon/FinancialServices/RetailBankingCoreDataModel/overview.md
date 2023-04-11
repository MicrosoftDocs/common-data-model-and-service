---
title: overview of RetailBankingCoreDataModel - Common Data Model | Microsoft Docs
description: RetailBankingCoreDataModel is a folder that contains standard entities related to the Common Data Model.
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/5/2023
ms.author: cdmditeam
---

# Overview of RetailBankingCoreDataModel


## Entities

|Name|Description|
|---|---|
|[Account](Account.md)|Business that represents a customer or potential customer\. The company that is billed in business transactions\.|
|[Bank](Bank.md)|The bank that the branch is associated with\.|
|[Branch](Branch.md)|The branch of the main bank, when borrower applies for a loan at a branch\.|
|[Contact](Contact.md)|Person with whom a business unit has a relationship, such as customer, supplier, and colleague\.|
|[Customerfinancialholding](Customerfinancialholding.md)|Financial holdings owned by the customer\.|
|[Fh_account](Fh_account.md)|A deposit account holding that allows the holder to make deposits and withdrawals through financial holding instruments\. An account can be interest bearing|
|[Fh_creditline](Fh_creditline.md)|A preset borrowing limit associated with a credit or charge card\.|
|[Fh_investment](Fh_investment.md)|A holding representing a portfolio of securities or other investible assets\.|
|[Fh_loan](Fh_loan.md)|Loans held by the customer with the financial institution\.|
|[Fh_saving](Fh_saving.md)|Savings accounts held by the customer at the financial institution\.|
|[Financialholding](Financialholding.md)|Accounts, loans, investments, credit lines and savings accounts held by a customer\.|
|[Financialholdinginstrument](Financialholdinginstrument.md)|Financial tools associated with financial holdings; a monetary contract between parties which has intrinsic monetary value or transfers value\. Provides an efficient flow and transfer of capital\.|
|[Fi_card](Fi_card.md)|A payment card issued by a bank to an account holder enabling the account holder to make payments or purchases, paying back the balance to the issuing bank, plus interest\.|
|[Fi_directdebit](Fi_directdebit.md)|An automated payment system whereby an account holder authorizes a creditor to debit the customer's bank account at regular intervals\.|
|[Fi_overdraft](Fi_overdraft.md)|An extension of credit associated with a checking account allowing the account holder to continue withdrawing funds when an account reaches zero\.|
|[Fi_standingorder](Fi_standingorder.md)|An instruction order from an account holder for a set amount of money to be removed from an account at regular intervals and paid to or transferred to another account\.|
|[Group](Group.md)|An association of several customers allowing e\.g\. the representation of households|
|[Groupfinancialholding](Groupfinancialholding.md)|Financial holdings associated with a Group, to be included in the group's total assets and liabilities\.|
|[Groupmember](Groupmember.md)|An association between a customer and a Group\.|
|[Lifemoment](Lifemoment.md)|Significant milestones in a customer's personal life which can impact their financial situation, such as attending college, marriage, having a child, retirement, etc\.|
|[Relationship](Relationship.md)|Denotes an association between one contact to another \(not as part of the larger group\) where there is not necessarily a direct association of finances\. For example, a spouse, lawyer, child or grandparent\.|
