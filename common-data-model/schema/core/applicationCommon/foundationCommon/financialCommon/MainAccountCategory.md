---
title: MainAccountCategory_
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/1/2019
ms.author: tpalmer
---
# Main Account Category

## Properties

Display Name: Main Account Category

Description: Provides categorization of main accounts

Latest Version: 0.8.1

Entity Definition on GitHub: [https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/MainAccountCategory.cdm.json](https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/MainAccountCategory.cdm.json)

## Instances

## Attributes - Summary

<table><tr><th>Name</th><th>Description</th><th>First Included in Instance</th></tr><tr><td>mainAccountCategoryId</td><td>The surrogate key of the main account category record</td><td> </td></tr><tr><td>name</td><td>The display name of the main account category</td><td> </td></tr><tr><td>description</td><td>The description of the main account category</td><td> </td></tr><tr><td>isClosed</td><td>Determines whether accounts of this category are closed for new transactions</td><td> </td></tr><tr><td>accountType</td><td>The common account type for accounts in this category, such as revenue or liability</td><td> </td></tr><tr><td>accountType_display</td><td>undefined</td><td> </td></tr></table>

## Attribute - Details

### mainAccountCategoryId

The surrogate key of the main account category record

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Account Category ID</td></tr><tr><td>description</td><td>The surrogate key of the main account category record</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.identifiedBy

names a specifc identity attribute to use with an entity

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>attribute</td><td>"MainAccountCategory_/hasAttributes/mainAccountCategoryId"</td><td>attribute</td><td>undefined</td></tr></table>

Definition:

```
"MainAccountCategory_/hasAttributes/mainAccountCategoryId"
```

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Main Account Category ID</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The surrogate key of the main account category record</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


### name

The display name of the main account category

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>The display name of the main account category</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The display name of the main account category</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


### description

The description of the main account category

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>description</td><td>The description of the main account category</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.description


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Description</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The description of the main account category</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


### isClosed

Determines whether accounts of this category are closed for new transactions

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Closed</td></tr><tr><td>description</td><td>Determines whether accounts of this category are closed for new transactions</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is Closed</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Determines whether accounts of this category are closed for new transactions</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


### accountType

The common account type for accounts in this category, such as revenue or liability

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account Type</td></tr><tr><td>description</td><td>The common account type for accounts in this category, such as revenue or liability</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td>[
  {
    "languageTag": "en",
    "displayText": "Blank",
    "attributeValue": "50",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "ProfitAndLoss",
    "attributeValue": "0",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Revenue",
    "attributeValue": "1",
    "displayOrder": "2"
  },
  {
    "languageTag": "en",
    "displayText": "Expense",
    "attributeValue": "2",
    "displayOrder": "3"
  },
  {
    "languageTag": "en",
    "displayText": "BalanceSheet",
    "attributeValue": "3",
    "displayOrder": "4"
  },
  {
    "languageTag": "en",
    "displayText": "Asset",
    "attributeValue": "4",
    "displayOrder": "5"
  },
  {
    "languageTag": "en",
    "displayText": "Liability",
    "attributeValue": "5",
    "displayOrder": "6"
  },
  {
    "languageTag": "en",
    "displayText": "Equity",
    "attributeValue": "6",
    "displayOrder": "7"
  }
]</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr><tr><td>en</td><td>Blank</td><td>50</td><td>0</td></tr><tr><td>en</td><td>ProfitAndLoss</td><td>0</td><td>1</td></tr><tr><td>en</td><td>Revenue</td><td>1</td><td>2</td></tr><tr><td>en</td><td>Expense</td><td>2</td><td>3</td></tr><tr><td>en</td><td>BalanceSheet</td><td>3</td><td>4</td></tr><tr><td>en</td><td>Asset</td><td>4</td><td>5</td></tr><tr><td>en</td><td>Liability</td><td>5</td><td>6</td></tr><tr><td>en</td><td>Equity</td><td>6</td><td>7</td></tr></table>
</td><td>any</td><td>undefined</td></tr></table>


##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Account Type</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The common account type for accounts in this category, such as revenue or liability</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


### accountType_display

undefined

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.displayText


##### is.readOnly


##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>accountType</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>


