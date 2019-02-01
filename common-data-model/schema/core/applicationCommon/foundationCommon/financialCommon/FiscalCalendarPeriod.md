---
title: FiscalCalendarPeriod_
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/1/2019
ms.author: tpalmer
---
# Fiscal Calendar Period

## Properties

Display Name: Fiscal Calendar Period

Description: Represents the period in which financial activity occurred, as defined by a fiscal calendar.

Latest Version: 0.8.1

Entity Definition on GitHub: [https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/FiscalCalendarPeriod.cdm.json](https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/FiscalCalendarPeriod.cdm.json)

## Instances

## Attributes - Summary

<table><tr><th>Name</th><th>Description</th><th>First Included in Instance</th></tr><tr><td>fiscalCalendarPeriodId</td><td>The surrogate key of the record</td><td> </td></tr><tr><td>fiscalCalendarName</td><td>The name of the calendar containing this period</td><td> </td></tr><tr><td>periodName</td><td>The name of the period</td><td> </td></tr><tr><td>periodOffset</td><td>The number of periods this period is offset from the current period for use in computations such as previous period</td><td> </td></tr><tr><td>yearName</td><td>The name of the year containing the period</td><td> </td></tr><tr><td>yearOffset</td><td>The number of years this year is offset from the current year for use in computations such as prior year</td><td> </td></tr><tr><td>quarter</td><td>The name of the quarter containing the period</td><td> </td></tr><tr><td>quarterOffset</td><td>The number of quarters this quarter is offset from the current quarter for use in computations such as same quarter previous year</td><td> </td></tr><tr><td>month</td><td>The month containing the period.</td><td> </td></tr></table>

## Attribute - Details

### fiscalCalendarPeriodId

The surrogate key of the record

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal Calendar Period ID</td></tr><tr><td>description</td><td>The surrogate key of the record</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.identifiedBy

names a specifc identity attribute to use with an entity

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>attribute</td><td>"FiscalCalendarPeriod_/hasAttributes/fiscalCalendarPeriodId"</td><td>attribute</td><td>undefined</td></tr></table>

Definition:

```
"FiscalCalendarPeriod_/hasAttributes/fiscalCalendarPeriodId"
```

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal Calendar Period ID</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The surrogate key of the record</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


### fiscalCalendarName

The name of the calendar containing this period

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal Calendar Name</td></tr><tr><td>description</td><td>The name of the calendar containing this period</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal Calendar Name</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The name of the calendar containing this period</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


### periodName

The name of the period

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period Name</td></tr><tr><td>description</td><td>The name of the period</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Period Name</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The name of the period</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


### periodOffset

The number of periods this period is offset from the current period for use in computations such as previous period

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period Offset</td></tr><tr><td>description</td><td>The number of periods this period is offset from the current period for use in computations such as previous period</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Period Offset</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The number of periods this period is offset from the current period for use in computations such as previous period</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


### yearName

The name of the year containing the period

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Year Name</td></tr><tr><td>description</td><td>The name of the year containing the period</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.calendar.year


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Year Name</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The name of the year containing the period</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


### yearOffset

The number of years this year is offset from the current year for use in computations such as prior year

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Year Offset</td></tr><tr><td>description</td><td>The number of years this year is offset from the current year for use in computations such as prior year</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Year Offset</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The number of years this year is offset from the current year for use in computations such as prior year</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


### quarter

The name of the quarter containing the period

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quarter</td></tr><tr><td>description</td><td>The name of the quarter containing the period</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.calendar.quarter


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quarter</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The name of the quarter containing the period</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


### quarterOffset

The number of quarters this quarter is offset from the current quarter for use in computations such as same quarter previous year

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quarter Offset</td></tr><tr><td>description</td><td>The number of quarters this quarter is offset from the current quarter for use in computations such as same quarter previous year</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quarter Offset</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The number of quarters this quarter is offset from the current quarter for use in computations such as same quarter previous year</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


### month

The month containing the period.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Month</td></tr><tr><td>description</td><td>The month containing the period.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### means.calendar


##### means.calendar.month


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Month</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The month containing the period.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


