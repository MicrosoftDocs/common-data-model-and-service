---
title: MainAccount
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/5/2019
ms.author: tpalmer
---

# Main Account

## Properties

Display Name: Main Account

Description: An account whose balance is displayed in major financial statements

Latest Version: 0.8.1

Entity Definition on GitHub: [https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/MainAccount.cdm.json](https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/MainAccount.cdm.json)

## Instances

[/core/applicationCommon/foundationCommon/financialCommon/MainAccount.cdm.json/MainAccount](MainAccount.md)

## Attributes - Summary

|Name|Description|First Included in Instance|
|---|---|---|
|[mainAccountId](#mainAccountId)|The surrogate key of the main account record|[financialCommon/MainAccount](MainAccount.md)|
|[name](#name)|The user-readable name of the main account|[financialCommon/MainAccount](MainAccount.md)|
|[number](#number)|The numerical designation of the account according to the chart of accounts, usually designed such that accounts of the same type have similar numbers|[financialCommon/MainAccount](MainAccount.md)|
|[mainAccountCategoryKey](#mainAccountCategoryKey)|The categorization of the main account, by which accounting aspects such as account type are defined|[financialCommon/MainAccount](MainAccount.md)|
|[currencyKey](#currencyKey)|The currency in which amounts held by this account are expressed|[financialCommon/MainAccount](MainAccount.md)|

## Attribute - Details

### <a name="mainAccountId">mainAccountId</a>

The surrogate key of the main account record

First included in: /core/applicationCommon/foundationCommon/financialCommon/MainAccount.cdm.json/MainAccount

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>MainAccountId</td></tr>
<tr><td>description</td><td>The surrogate key of the main account record</td></tr>
<tr><td>isPrimaryKey</td><td>true</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the mainAccountId attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.identifiedBy

names a specifc identity attribute to use with an entity

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>attribute</td><td>"MainAccount_/hasAttributes/mainAccountId"</td><td>attribute</td><td></td></tr>
</table>

Definition:

```
"MainAccount_/hasAttributes/mainAccountId"
```

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>MainAccountId</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The surrogate key of the main account record</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

</details>

### <a name="name">name</a>

The user-readable name of the main account

First included in: /core/applicationCommon/foundationCommon/financialCommon/MainAccount.cdm.json/MainAccount

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Name</td></tr>
<tr><td>description</td><td>The user-readable name of the main account</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### means.identity.name

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Name</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The user-readable name of the main account</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

</details>

### <a name="number">number</a>

The numerical designation of the account according to the chart of accounts, usually designed such that accounts of the same type have similar numbers

First included in: /core/applicationCommon/foundationCommon/financialCommon/MainAccount.cdm.json/MainAccount

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Number</td></tr>
<tr><td>description</td><td>The numerical designation of the account according to the chart of accounts, usually designed such that accounts of the same type have similar numbers</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the number attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Number</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The numerical designation of the account according to the chart of accounts, usually designed such that accounts of the same type have similar numbers</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

</details>

### <a name="mainAccountCategoryKey">mainAccountCategoryKey</a>

The categorization of the main account, by which accounting aspects such as account type are defined

First included in: /core/applicationCommon/foundationCommon/financialCommon/MainAccount.cdm.json/MainAccount

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Main Account Category Key</td></tr>
<tr><td>description</td><td>The categorization of the main account, by which accounting aspects such as account type are defined</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the mainAccountCategoryKey attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Main Account Category Key</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The categorization of the main account, by which accounting aspects such as account type are defined</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.linkedEntity.identifier

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.

</details>

### <a name="currencyKey">currencyKey</a>

The currency in which amounts held by this account are expressed

First included in: /core/applicationCommon/foundationCommon/financialCommon/MainAccount.cdm.json/MainAccount

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Currency Key</td></tr>
<tr><td>description</td><td>The currency in which amounts held by this account are expressed</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the currencyKey attribute are listed below.</summary>

- ##### is.dataFormat.character

- ##### is.dataFormat.big

- ##### is.dataFormat.array

- ##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Currency Key</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The currency in which amounts held by this account are expressed</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

- ##### is.linkedEntity.identifier

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.

</details>

