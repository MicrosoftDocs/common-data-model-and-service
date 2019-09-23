---
title: Ledger - Common Data Model | Microsoft Docs
description: The collection of all accounts making up the central repository of accounting data for a company.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Ledger

The collection of all accounts making up the central repository of accounting data for a company.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/Ledger.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/financialCommon/Ledger  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ledgerId](#ledgerId)|The surrogate key of the ledger record|<a href="Ledger.md" target="_blank">financialCommon/Ledger</a>|
|[name](#name)|The user-readable name of the ledger|<a href="Ledger.md" target="_blank">financialCommon/Ledger</a>|
|[description](#description)|The description of the ledger|<a href="Ledger.md" target="_blank">financialCommon/Ledger</a>|
|[companyKey](#companyKey)|The company for which the ledger stores financial information|<a href="Ledger.md" target="_blank">financialCommon/Ledger</a>|
|[accountingCurrencyKey](#accountingCurrencyKey)|The currency in which all amounts in the ledger are expressed|<a href="Ledger.md" target="_blank">financialCommon/Ledger</a>|

### <a href=#ledgerId name="ledgerId">ledgerId</a>

The surrogate key of the ledger record  
First included in: financialCommon/Ledger (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>LedgerId</td></tr><tr><td>description</td><td>The surrogate key of the ledger record</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#name name="name">name</a>

The user-readable name of the ledger  
First included in: financialCommon/Ledger (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The user-readable name of the ledger</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#description name="description">description</a>

The description of the ledger  
First included in: financialCommon/Ledger (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>The description of the ledger</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#companyKey name="companyKey">companyKey</a>

The company for which the ledger stores financial information  
First included in: financialCommon/Ledger (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company Key</td></tr><tr><td>description</td><td>The company for which the ledger stores financial information</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#accountingCurrencyKey name="accountingCurrencyKey">accountingCurrencyKey</a>

The currency in which all amounts in the ledger are expressed  
First included in: financialCommon/Ledger (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accounting Currency Key</td></tr><tr><td>description</td><td>The currency in which all amounts in the ledger are expressed</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>
