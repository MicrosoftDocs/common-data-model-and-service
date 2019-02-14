---
title: MainAccount
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/13/2019
ms.author: tpalmer
---

# Main Account

An account whose balance is displayed in major financial statements  
  
Latest version (0.8.1) of the json entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/MainAccount.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below:  

financialCommon/MainAccount  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

- **is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>0.8.1</td><td>string</td><td>semantic version number of the entity</td></tr></table>

- **is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MainAccount/hasAttributes/mainAccountId](#mainAccountId)</td><td>attribute</td><td></td></tr></table>

- **is.CDM.attributeGroup**  
  identifies standard groups of attributes in CDM entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>groupList</td><td><table><tr><th>attributeGroupReference</th></tr><tr><td>/core/applicationCommon/foundationCommon<br>/financeCommon/MainAccount.cdm.json/MainAccount<br>/hasAttributes/attributesAddedAtThisScope</td></tr></table></td><td>entity</td><td></td></tr></table>

- **is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Main Account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>An account whose balance is displayed in major financial statements</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

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
First included in: financialCommon/MainAccount  (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>MainAccountId</td></tr><tr><td>description</td><td>The surrogate key of the main account record</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

#### Traits

<details>
<summary>List of traits for the  mainAccountId  attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MainAccount/hasAttributes/mainAccountId](#mainAccountId)</td><td>attribute</td><td></td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>MainAccountId</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The surrogate key of the main account record</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

### <a href=#name name="name">name</a>

The user-readable name of the main account  
First included in: financialCommon/MainAccount  (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The user-readable name of the main account</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

#### Traits

<details>
<summary>List of traits for the  name  attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **means.identity.name**  
- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The user-readable name of the main account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

### <a href=#number name="number">number</a>

The numerical designation of the account according to the chart of accounts, usually designed such that accounts of the same type have similar numbers  
First included in: financialCommon/MainAccount  (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number</td></tr><tr><td>description</td><td>The numerical designation of the account according to the chart of accounts, usually designed such that accounts of the same type have similar numbers</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

#### Traits

<details>
<summary>List of traits for the  number  attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The numerical designation of the account according to the chart of accounts, usually designed such that accounts of the same type have similar numbers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

### <a href=#mainAccountCategoryKey name="mainAccountCategoryKey">mainAccountCategoryKey</a>

The categorization of the main account, by which accounting aspects such as account type are defined  
First included in: financialCommon/MainAccount  (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Account Category Key</td></tr><tr><td>description</td><td>The categorization of the main account, by which accounting aspects such as account type are defined</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

#### Traits

<details>
<summary>List of traits for the  mainAccountCategoryKey  attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Main Account Category Key</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The categorization of the main account, by which accounting aspects such as account type are defined</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  

</details>

### <a href=#currencyKey name="currencyKey">currencyKey</a>

The currency in which amounts held by this account are expressed  
First included in: financialCommon/MainAccount  (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency Key</td></tr><tr><td>description</td><td>The currency in which amounts held by this account are expressed</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

#### Traits

<details>
<summary>List of traits for the  currencyKey  attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Currency Key</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The currency in which amounts held by this account are expressed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  

</details>
