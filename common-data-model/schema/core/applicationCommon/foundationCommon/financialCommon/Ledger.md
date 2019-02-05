---
title: Ledger
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/5/2019
ms.author: tpalmer
---

# Ledger

## Properties

Display Name: Ledger

Description: The collection of all accounts making up the central repository of accounting data for a company.

Latest Version: 0.8.1

Entity Definition on GitHub: [https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/Ledger.cdm.json](https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/Ledger.cdm.json)

## Instances

[/core/applicationCommon/foundationCommon/financialCommon/Ledger.cdm.json/Ledger](Ledger.md)

## Attributes - Summary

|Name|Description|First Included in Instance|
|---|---|---|
|[ledgerId](#ledgerId)|The surrogate key of the ledger record|[financialCommon/Ledger](Ledger.md)|
|[name](#name)|The user-readable name of the ledger|[financialCommon/Ledger](Ledger.md)|
|[description](#description)|The description of the ledger|[financialCommon/Ledger](Ledger.md)|
|[companyKey](#companyKey)|The company for which the ledger stores financial information|[financialCommon/Ledger](Ledger.md)|
|[accountingCurrencyKey](#accountingCurrencyKey)|The currency in which all amounts in the ledger are expressed|[financialCommon/Ledger](Ledger.md)|

## Attribute - Details

### <a name="ledgerId">ledgerId</a>

The surrogate key of the ledger record

First included in: /core/applicationCommon/foundationCommon/financialCommon/Ledger.cdm.json/Ledger

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>LedgerId</td></tr>
<tr><td>description</td><td>The surrogate key of the ledger record</td></tr>
<tr><td>isPrimaryKey</td><td>true</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.identifiedBy

names a specifc identity attribute to use with an entity

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>attribute</td><td>"Ledger_/hasAttributes/ledgerId"</td><td>attribute</td><td></td></tr>
</table>

Definition:

```
"Ledger_/hasAttributes/ledgerId"
```

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>LedgerId</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The surrogate key of the ledger record</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

</details>

### <a name="name">name</a>

The user-readable name of the ledger

First included in: /core/applicationCommon/foundationCommon/financialCommon/Ledger.cdm.json/Ledger

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Name</td></tr>
<tr><td>description</td><td>The user-readable name of the ledger</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.identity.name

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Name</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The user-readable name of the ledger</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

</details>

### <a name="description">description</a>

The description of the ledger

First included in: /core/applicationCommon/foundationCommon/financialCommon/Ledger.cdm.json/Ledger

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Description</td></tr>
<tr><td>description</td><td>The description of the ledger</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.description

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Description</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The description of the ledger</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

</details>

### <a name="companyKey">companyKey</a>

The company for which the ledger stores financial information

First included in: /core/applicationCommon/foundationCommon/financialCommon/Ledger.cdm.json/Ledger

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Company Key</td></tr>
<tr><td>description</td><td>The company for which the ledger stores financial information</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Company Key</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The company for which the ledger stores financial information</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.linkedEntity.identifier

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.

</details>

### <a name="accountingCurrencyKey">accountingCurrencyKey</a>

The currency in which all amounts in the ledger are expressed

First included in: /core/applicationCommon/foundationCommon/financialCommon/Ledger.cdm.json/Ledger

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Accounting Currency Key</td></tr>
<tr><td>description</td><td>The currency in which all amounts in the ledger are expressed</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Accounting Currency Key</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The currency in which all amounts in the ledger are expressed</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.linkedEntity.identifier

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.

</details>

