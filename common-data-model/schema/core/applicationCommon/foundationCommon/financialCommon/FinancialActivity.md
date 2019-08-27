---
title: FinancialActivity - Common Data Model | Microsoft Docs
description: Summarization of financial activity for a ledger, date, account, and dimension combination
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Financial Activity

Summarization of financial activity for a ledger, date, account, and dimension combination  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/FinancialActivity.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/financialCommon/FinancialActivity  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[financialActivityId](#financialActivityId)|The surrogate key of the record|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[mainAccountCategoryKey](#mainAccountCategoryKey)|The category of the main account for this activity, denormalized for reporting|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[mainAccountKey](#mainAccountKey)|The main account containing this financial activity|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[companyKey](#companyKey)|The company for which this financial activity occurred|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[transactionCurrencyKey](#transactionCurrencyKey)|The currency in which the source transaction occurred|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[fiscalCalendarPeriodKey](#fiscalCalendarPeriodKey)|The fiscal period in which the financial activity occurred|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[ledgerDimensionDisplayValue](#ledgerDimensionDisplayValue)|A denormalization of the full string representing the main account plus additional dimension values|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[transactionCurrencyCode](#transactionCurrencyCode)|A denormalization of the currency code in which the source transaction occurred|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[accountingCurrencyAmount](#accountingCurrencyAmount)|The amount of the financial activity expressed in the accounting currency|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[accountingDate](#accountingDate)|The date on which the financial activity was recognized|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[ledgerId](#ledgerId)|The ledger containing this financial activity|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|

### <a href=#financialActivityId name="financialActivityId">financialActivityId</a>

The surrogate key of the record  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Financial Activity ID</td></tr><tr><td>description</td><td>The surrogate key of the record</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#mainAccountCategoryKey name="mainAccountCategoryKey">mainAccountCategoryKey</a>

The category of the main account for this activity, denormalized for reporting  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Account Category Key</td></tr><tr><td>description</td><td>The category of the main account for this activity, denormalized for reporting</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#mainAccountKey name="mainAccountKey">mainAccountKey</a>

The main account containing this financial activity  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Account Key</td></tr><tr><td>description</td><td>The main account containing this financial activity</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#companyKey name="companyKey">companyKey</a>

The company for which this financial activity occurred  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company Key</td></tr><tr><td>description</td><td>The company for which this financial activity occurred</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#transactionCurrencyKey name="transactionCurrencyKey">transactionCurrencyKey</a>

The currency in which the source transaction occurred  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Currency Key</td></tr><tr><td>description</td><td>The currency in which the source transaction occurred</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#fiscalCalendarPeriodKey name="fiscalCalendarPeriodKey">fiscalCalendarPeriodKey</a>

The fiscal period in which the financial activity occurred  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal Calendar Period Key</td></tr><tr><td>description</td><td>The fiscal period in which the financial activity occurred</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#ledgerDimensionDisplayValue name="ledgerDimensionDisplayValue">ledgerDimensionDisplayValue</a>

A denormalization of the full string representing the main account plus additional dimension values  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ledger Dimension Display Value</td></tr><tr><td>description</td><td>A denormalization of the full string representing the main account plus additional dimension values</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#transactionCurrencyCode name="transactionCurrencyCode">transactionCurrencyCode</a>

A denormalization of the currency code in which the source transaction occurred  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Currency Code</td></tr><tr><td>description</td><td>A denormalization of the currency code in which the source transaction occurred</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#accountingCurrencyAmount name="accountingCurrencyAmount">accountingCurrencyAmount</a>

The amount of the financial activity expressed in the accounting currency  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>AccountingCurrencyAmount</td></tr><tr><td>description</td><td>The amount of the financial activity expressed in the accounting currency</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr></table>

### <a href=#accountingDate name="accountingDate">accountingDate</a>

The date on which the financial activity was recognized  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>AccountingDate</td></tr><tr><td>description</td><td>The date on which the financial activity was recognized</td></tr><tr><td>dataFormat</td><td>Date</td></tr></table>

### <a href=#ledgerId name="ledgerId">ledgerId</a>

The ledger containing this financial activity  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ledger</td></tr><tr><td>description</td><td>The ledger containing this financial activity</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>
