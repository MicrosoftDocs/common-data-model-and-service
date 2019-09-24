---
title: MainAccount - Common Data Model | Microsoft Docs
description: An account whose balance is displayed in major financial statements
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Main Account

An account whose balance is displayed in major financial statements  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/MainAccount.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/financialCommon/MainAccount  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[mainAccountId](#mainAccountId)|The surrogate key of the main account record|<a href="MainAccount.md" target="_blank">financialCommon/MainAccount</a>|
|[name](#name)|The user-readable name of the main account|<a href="MainAccount.md" target="_blank">financialCommon/MainAccount</a>|
|[number](#number)|The numerical designation of the account according to the chart of accounts, usually designed such that accounts of the same type have similar numbers|<a href="MainAccount.md" target="_blank">financialCommon/MainAccount</a>|
|[mainAccountCategoryKey](#mainAccountCategoryKey)|The categorization of the main account, by which accounting aspects such as account type are defined|<a href="MainAccount.md" target="_blank">financialCommon/MainAccount</a>|
|[currencyKey](#currencyKey)|The currency in which amounts held by this account are expressed|<a href="MainAccount.md" target="_blank">financialCommon/MainAccount</a>|

### <a href=#mainAccountId name="mainAccountId">mainAccountId</a>

The surrogate key of the main account record  
First included in: financialCommon/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>MainAccountId</td></tr><tr><td>description</td><td>The surrogate key of the main account record</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#name name="name">name</a>

The user-readable name of the main account  
First included in: financialCommon/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The user-readable name of the main account</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#number name="number">number</a>

The numerical designation of the account according to the chart of accounts, usually designed such that accounts of the same type have similar numbers  
First included in: financialCommon/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number</td></tr><tr><td>description</td><td>The numerical designation of the account according to the chart of accounts, usually designed such that accounts of the same type have similar numbers</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#mainAccountCategoryKey name="mainAccountCategoryKey">mainAccountCategoryKey</a>

The categorization of the main account, by which accounting aspects such as account type are defined  
First included in: financialCommon/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Account Category Key</td></tr><tr><td>description</td><td>The categorization of the main account, by which accounting aspects such as account type are defined</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#currencyKey name="currencyKey">currencyKey</a>

The currency in which amounts held by this account are expressed  
First included in: financialCommon/MainAccount (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency Key</td></tr><tr><td>description</td><td>The currency in which amounts held by this account are expressed</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>
