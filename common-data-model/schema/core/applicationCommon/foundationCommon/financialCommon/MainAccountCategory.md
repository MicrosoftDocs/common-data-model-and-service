---
title: MainAccountCategory - Common Data Model | Microsoft Docs
description: Provides categorization of main accounts
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 9/19/2019
ms.author: nebanfic
---

# Main Account Category

Provides categorization of main accounts  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/MainAccountCategory.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/financialCommon/MainAccountCategory  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[mainAccountCategoryId](#mainAccountCategoryId)|The surrogate key of the main account category record|<a href="MainAccountCategory.md" target="_blank">financialCommon/MainAccountCategory</a>|
|[name](#name)|The display name of the main account category|<a href="MainAccountCategory.md" target="_blank">financialCommon/MainAccountCategory</a>|
|[description](#description)|The description of the main account category|<a href="MainAccountCategory.md" target="_blank">financialCommon/MainAccountCategory</a>|
|[isClosed](#isClosed)|Determines whether accounts of this category are closed for new transactions|<a href="MainAccountCategory.md" target="_blank">financialCommon/MainAccountCategory</a>|
|[accountType](#accountType)|The common account type for accounts in this category, such as revenue or liability|<a href="MainAccountCategory.md" target="_blank">financialCommon/MainAccountCategory</a>|
|[accountType_display](#accountType_display)||<a href="MainAccountCategory.md" target="_blank">financialCommon/MainAccountCategory</a>|

### <a href=#mainAccountCategoryId name="mainAccountCategoryId">mainAccountCategoryId</a>

The surrogate key of the main account category record  
First included in: financialCommon/MainAccountCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Account Category ID</td></tr><tr><td>description</td><td>The surrogate key of the main account category record</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#name name="name">name</a>

The display name of the main account category  
First included in: financialCommon/MainAccountCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The display name of the main account category</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#description name="description">description</a>

The description of the main account category  
First included in: financialCommon/MainAccountCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>The description of the main account category</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#isClosed name="isClosed">isClosed</a>

Determines whether accounts of this category are closed for new transactions  
First included in: financialCommon/MainAccountCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Closed</td></tr><tr><td>description</td><td>Determines whether accounts of this category are closed for new transactions</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr></table>

### <a href=#accountType name="accountType">accountType</a>

The common account type for accounts in this category, such as revenue or liability  
First included in: financialCommon/MainAccountCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account Type</td></tr><tr><td>description</td><td>The common account type for accounts in this category, such as revenue or liability</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Blank</td><td>50</td></tr><tr><td>en</td><td>ProfitAndLoss</td><td>0</td></tr><tr><td>en</td><td>Revenue</td><td>1</td></tr><tr><td>en</td><td>Expense</td><td>2</td></tr><tr><td>en</td><td>BalanceSheet</td><td>3</td></tr><tr><td>en</td><td>Asset</td><td>4</td></tr><tr><td>en</td><td>Liability</td><td>5</td></tr><tr><td>en</td><td>Equity</td><td>6</td></tr></table></td></tr></table>

### <a href=#accountType_display name="accountType_display">accountType_display</a>

First included in: financialCommon/MainAccountCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>
