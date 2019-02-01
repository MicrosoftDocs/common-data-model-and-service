---
title: MainAccount_
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/1/2019
ms.author: tpalmer
---
# Main Account

## Properties

Display Name: Main Account

Description: An account whose balance is displayed in major financial statements

Latest Version: 0.8.1

Entity Definition on GitHub: [https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/MainAccount.cdm.json](https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/MainAccount.cdm.json)

## Instances

## Attributes - Summary

<table><tr><th>Name</th><th>Description</th><th>First Included in Instance</th></tr><tr><td>mainAccountId</td><td>The surrogate key of the main account record</td><td> </td></tr><tr><td>name</td><td>The user-readable name of the main account</td><td> </td></tr><tr><td>number</td><td>The numerical designation of the account according to the chart of accounts, usually designed such that accounts of the same type have similar numbers</td><td> </td></tr><tr><td>mainAccountCategoryKey</td><td>The categorization of the main account, by which accounting aspects such as account type are defined</td><td> </td></tr><tr><td>currencyKey</td><td>The currency in which amounts held by this account are expressed</td><td> </td></tr></table>

## Attribute - Details

### mainAccountId

The surrogate key of the main account record

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>MainAccountId</td></tr><tr><td>description</td><td>The surrogate key of the main account record</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.identifiedBy

names a specifc identity attribute to use with an entity

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>attribute</td><td>"MainAccount_/hasAttributes/mainAccountId"</td><td>attribute</td><td>undefined</td></tr></table>

Definition:

```
"MainAccount_/hasAttributes/mainAccountId"
```

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>MainAccountId</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The surrogate key of the main account record</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


### name

The user-readable name of the main account

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The user-readable name of the main account</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.identity.name


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The user-readable name of the main account</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


### number

The numerical designation of the account according to the chart of accounts, usually designed such that accounts of the same type have similar numbers

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number</td></tr><tr><td>description</td><td>The numerical designation of the account according to the chart of accounts, usually designed such that accounts of the same type have similar numbers</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Number</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The numerical designation of the account according to the chart of accounts, usually designed such that accounts of the same type have similar numbers</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


### mainAccountCategoryKey

The categorization of the main account, by which accounting aspects such as account type are defined

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Account Category Key</td></tr><tr><td>description</td><td>The categorization of the main account, by which accounting aspects such as account type are defined</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Main Account Category Key</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The categorization of the main account, by which accounting aspects such as account type are defined</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.linkedEntity.identifier

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.


### currencyKey

The currency in which amounts held by this account are expressed

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency Key</td></tr><tr><td>description</td><td>The currency in which amounts held by this account are expressed</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Currency Key</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The currency in which amounts held by this account are expressed</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.linkedEntity.identifier

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.


