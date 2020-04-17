---
title: MainAccountCategory - Common Data Model | Microsoft Docs
description: Provides categorization of main accounts
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# Main Account Category

Provides categorization of main accounts  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/MainAccountCategory.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MainAccountCategory/(resolvedAttributes)/mainAccountCategoryId](#mainAccountCategoryId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.attributeGroup**  
  identifies standard groups of attributes in CDM entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>groupList</td><td><table><tr><th>attributeGroupReference</th></tr><tr><td>/core/applicationCommon/foundationCommon<br>/financeCommon/MainAccountCategory.cdm.json<br>/MainAccountCategory/hasAttributes<br>/attributesAddedAtThisScope</td></tr></table></td><td>entity</td><td></td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Main Account Category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Provides categorization of main accounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

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

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Account Category ID</td></tr><tr><td>description</td><td>The surrogate key of the main account category record</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the mainAccountCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MainAccountCategory/(resolvedAttributes)/mainAccountCategoryId](#mainAccountCategoryId)</td><td>attribute</td><td></td></tr></table>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Main Account Category ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The surrogate key of the main account category record</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#name name="name">name</a>

The display name of the main account category  
First included in: financialCommon/MainAccountCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The display name of the main account category</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The display name of the main account category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#description name="description">description</a>

The description of the main account category  
First included in: financialCommon/MainAccountCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>The description of the main account category</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.description**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The description of the main account category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#isClosed name="isClosed">isClosed</a>

Determines whether accounts of this category are closed for new transactions  
First included in: financialCommon/MainAccountCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Closed</td></tr><tr><td>description</td><td>Determines whether accounts of this category are closed for new transactions</td></tr><tr><td>dataFormat</td><td>boolean</td></tr></table>

#### Traits

<details>
<summary>List of traits for the isClosed attribute are listed below.</summary>

**is.dataFormat.boolean**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is Closed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Determines whether accounts of this category are closed for new transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.boolean**  
</details>

### <a href=#accountType name="accountType">accountType</a>

The common account type for accounts in this category, such as revenue or liability  
First included in: financialCommon/MainAccountCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account Type</td></tr><tr><td>description</td><td>The common account type for accounts in this category, such as revenue or liability</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Blank</td><td>50</td></tr><tr><td>en</td><td>ProfitAndLoss</td><td>0</td></tr><tr><td>en</td><td>Revenue</td><td>1</td></tr><tr><td>en</td><td>Expense</td><td>2</td></tr><tr><td>en</td><td>BalanceSheet</td><td>3</td></tr><tr><td>en</td><td>Asset</td><td>4</td></tr><tr><td>en</td><td>Liability</td><td>5</td></tr><tr><td>en</td><td>Equity</td><td>6</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the accountType attribute are listed below.</summary>

**is.dataFormat.integer**  
**does.haveDefault**  
An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Blank</td><td>50</td></tr><tr><td>en</td><td>ProfitAndLoss</td><td>0</td></tr><tr><td>en</td><td>Revenue</td><td>1</td></tr><tr><td>en</td><td>Expense</td><td>2</td></tr><tr><td>en</td><td>BalanceSheet</td><td>3</td></tr><tr><td>en</td><td>Asset</td><td>4</td></tr><tr><td>en</td><td>Liability</td><td>5</td></tr><tr><td>en</td><td>Equity</td><td>6</td></tr></table></td><td>any</td><td></td></tr></table>

**is.constrainedList**  
the values of an attribute are taken from or looked up from a fixed list of possibilities  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Account Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The common account type for accounts in this category, such as revenue or liability</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#accountType_display name="accountType_display">accountType_display</a>

First included in: financialCommon/MainAccountCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the accountType_display attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**means.reference.displayText**  
**is.readOnly**  
**is.addedInSupportOf**  
<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>"accountType"</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
