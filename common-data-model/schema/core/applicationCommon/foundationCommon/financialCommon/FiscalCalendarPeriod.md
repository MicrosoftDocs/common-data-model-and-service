---
title: FiscalCalendarPeriod
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/5/2019
ms.author: tpalmer
---

# Fiscal Calendar Period

## Properties

Display Name: Fiscal Calendar Period

Description: Represents the period in which financial activity occurred, as defined by a fiscal calendar.

Latest Version: 0.8.1

Entity Definition on GitHub: [https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/FiscalCalendarPeriod.cdm.json](https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/FiscalCalendarPeriod.cdm.json)

## Instances

[/core/applicationCommon/foundationCommon/financialCommon/FiscalCalendarPeriod.cdm.json/FiscalCalendarPeriod](FiscalCalendarPeriod.md)

## Attributes - Summary

|Name|Description|First Included in Instance|
|---|---|---|
|[fiscalCalendarPeriodId](#fiscalCalendarPeriodId)|The surrogate key of the record|[financialCommon/FiscalCalendarPeriod](FiscalCalendarPeriod.md)|
|[fiscalCalendarName](#fiscalCalendarName)|The name of the calendar containing this period|[financialCommon/FiscalCalendarPeriod](FiscalCalendarPeriod.md)|
|[periodName](#periodName)|The name of the period|[financialCommon/FiscalCalendarPeriod](FiscalCalendarPeriod.md)|
|[periodOffset](#periodOffset)|The number of periods this period is offset from the current period for use in computations such as previous period|[financialCommon/FiscalCalendarPeriod](FiscalCalendarPeriod.md)|
|[yearName](#yearName)|The name of the year containing the period|[financialCommon/FiscalCalendarPeriod](FiscalCalendarPeriod.md)|
|[yearOffset](#yearOffset)|The number of years this year is offset from the current year for use in computations such as prior year|[financialCommon/FiscalCalendarPeriod](FiscalCalendarPeriod.md)|
|[quarter](#quarter)|The name of the quarter containing the period|[financialCommon/FiscalCalendarPeriod](FiscalCalendarPeriod.md)|
|[quarterOffset](#quarterOffset)|The number of quarters this quarter is offset from the current quarter for use in computations such as same quarter previous year|[financialCommon/FiscalCalendarPeriod](FiscalCalendarPeriod.md)|
|[month](#month)|The month containing the period.|[financialCommon/FiscalCalendarPeriod](FiscalCalendarPeriod.md)|

## Attribute - Details

### <a name="fiscalCalendarPeriodId">fiscalCalendarPeriodId</a>

The surrogate key of the record

First included in: /core/applicationCommon/foundationCommon/financialCommon/FiscalCalendarPeriod.cdm.json/FiscalCalendarPeriod

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Fiscal Calendar Period ID</td></tr>
<tr><td>description</td><td>The surrogate key of the record</td></tr>
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
<tr><td>attribute</td><td>"FiscalCalendarPeriod_/hasAttributes/fiscalCalendarPeriodId"</td><td>attribute</td><td></td></tr>
</table>

Definition:

```
"FiscalCalendarPeriod_/hasAttributes/fiscalCalendarPeriodId"
```

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Fiscal Calendar Period ID</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The surrogate key of the record</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

</details>

### <a name="fiscalCalendarName">fiscalCalendarName</a>

The name of the calendar containing this period

First included in: /core/applicationCommon/foundationCommon/financialCommon/FiscalCalendarPeriod.cdm.json/FiscalCalendarPeriod

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Fiscal Calendar Name</td></tr>
<tr><td>description</td><td>The name of the calendar containing this period</td></tr>
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
<tr><td>en</td><td>Fiscal Calendar Name</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The name of the calendar containing this period</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

</details>

### <a name="periodName">periodName</a>

The name of the period

First included in: /core/applicationCommon/foundationCommon/financialCommon/FiscalCalendarPeriod.cdm.json/FiscalCalendarPeriod

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Period Name</td></tr>
<tr><td>description</td><td>The name of the period</td></tr>
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
<tr><td>en</td><td>Period Name</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The name of the period</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

</details>

### <a name="periodOffset">periodOffset</a>

The number of periods this period is offset from the current period for use in computations such as previous period

First included in: /core/applicationCommon/foundationCommon/financialCommon/FiscalCalendarPeriod.cdm.json/FiscalCalendarPeriod

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Period Offset</td></tr>
<tr><td>description</td><td>The number of periods this period is offset from the current period for use in computations such as previous period</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Period Offset</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The number of periods this period is offset from the current period for use in computations such as previous period</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

</details>

### <a name="yearName">yearName</a>

The name of the year containing the period

First included in: /core/applicationCommon/foundationCommon/financialCommon/FiscalCalendarPeriod.cdm.json/FiscalCalendarPeriod

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Year Name</td></tr>
<tr><td>description</td><td>The name of the year containing the period</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.calendar.year

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Year Name</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The name of the year containing the period</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

</details>

### <a name="yearOffset">yearOffset</a>

The number of years this year is offset from the current year for use in computations such as prior year

First included in: /core/applicationCommon/foundationCommon/financialCommon/FiscalCalendarPeriod.cdm.json/FiscalCalendarPeriod

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Year Offset</td></tr>
<tr><td>description</td><td>The number of years this year is offset from the current year for use in computations such as prior year</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Year Offset</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The number of years this year is offset from the current year for use in computations such as prior year</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

</details>

### <a name="quarter">quarter</a>

The name of the quarter containing the period

First included in: /core/applicationCommon/foundationCommon/financialCommon/FiscalCalendarPeriod.cdm.json/FiscalCalendarPeriod

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Quarter</td></tr>
<tr><td>description</td><td>The name of the quarter containing the period</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.calendar.quarter

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Quarter</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The name of the quarter containing the period</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

</details>

### <a name="quarterOffset">quarterOffset</a>

The number of quarters this quarter is offset from the current quarter for use in computations such as same quarter previous year

First included in: /core/applicationCommon/foundationCommon/financialCommon/FiscalCalendarPeriod.cdm.json/FiscalCalendarPeriod

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Quarter Offset</td></tr>
<tr><td>description</td><td>The number of quarters this quarter is offset from the current quarter for use in computations such as same quarter previous year</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Quarter Offset</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The number of quarters this quarter is offset from the current quarter for use in computations such as same quarter previous year</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

</details>

### <a name="month">month</a>

The month containing the period.

First included in: /core/applicationCommon/foundationCommon/financialCommon/FiscalCalendarPeriod.cdm.json/FiscalCalendarPeriod

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Month</td></tr>
<tr><td>description</td><td>The month containing the period.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
</table>

#### Traits

<details>
<summary>Traits details.</summary>

##### is.dataFormat.integer

##### means.calendar

##### means.calendar.month

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Month</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The month containing the period.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

</details>

