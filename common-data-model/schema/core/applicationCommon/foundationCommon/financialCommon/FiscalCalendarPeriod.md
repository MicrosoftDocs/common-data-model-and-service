---
title: FiscalCalendarPeriod - Common Data Model | Microsoft Docs
description: Represents the period in which financial activity occurred, as defined by a fiscal calendar.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 4/8/2019
ms.author: nebanfic
---

# Fiscal Calendar Period

Represents the period in which financial activity occurred, as defined by a fiscal calendar.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/FiscalCalendarPeriod.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/financialCommon/FiscalCalendarPeriod  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[fiscalCalendarPeriodId](#fiscalCalendarPeriodId)|The surrogate key of the record|<a href="FiscalCalendarPeriod.md" target="_blank">financialCommon/FiscalCalendarPeriod</a>|
|[fiscalCalendarName](#fiscalCalendarName)|The name of the calendar containing this period|<a href="FiscalCalendarPeriod.md" target="_blank">financialCommon/FiscalCalendarPeriod</a>|
|[periodName](#periodName)|The name of the period|<a href="FiscalCalendarPeriod.md" target="_blank">financialCommon/FiscalCalendarPeriod</a>|
|[periodOffset](#periodOffset)|The number of periods this period is offset from the current period for use in computations such as previous period|<a href="FiscalCalendarPeriod.md" target="_blank">financialCommon/FiscalCalendarPeriod</a>|
|[yearName](#yearName)|The name of the year containing the period|<a href="FiscalCalendarPeriod.md" target="_blank">financialCommon/FiscalCalendarPeriod</a>|
|[yearOffset](#yearOffset)|The number of years this year is offset from the current year for use in computations such as prior year|<a href="FiscalCalendarPeriod.md" target="_blank">financialCommon/FiscalCalendarPeriod</a>|
|[quarter](#quarter)|The name of the quarter containing the period|<a href="FiscalCalendarPeriod.md" target="_blank">financialCommon/FiscalCalendarPeriod</a>|
|[quarterOffset](#quarterOffset)|The number of quarters this quarter is offset from the current quarter for use in computations such as same quarter previous year|<a href="FiscalCalendarPeriod.md" target="_blank">financialCommon/FiscalCalendarPeriod</a>|
|[month](#month)|The month containing the period.|<a href="FiscalCalendarPeriod.md" target="_blank">financialCommon/FiscalCalendarPeriod</a>|

### <a href=#fiscalCalendarPeriodId name="fiscalCalendarPeriodId">fiscalCalendarPeriodId</a>

The surrogate key of the record  
First included in: financialCommon/FiscalCalendarPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal Calendar Period ID</td></tr><tr><td>description</td><td>The surrogate key of the record</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#fiscalCalendarName name="fiscalCalendarName">fiscalCalendarName</a>

The name of the calendar containing this period  
First included in: financialCommon/FiscalCalendarPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal Calendar Name</td></tr><tr><td>description</td><td>The name of the calendar containing this period</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#periodName name="periodName">periodName</a>

The name of the period  
First included in: financialCommon/FiscalCalendarPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period Name</td></tr><tr><td>description</td><td>The name of the period</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#periodOffset name="periodOffset">periodOffset</a>

The number of periods this period is offset from the current period for use in computations such as previous period  
First included in: financialCommon/FiscalCalendarPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period Offset</td></tr><tr><td>description</td><td>The number of periods this period is offset from the current period for use in computations such as previous period</td></tr><tr><td>dataFormat</td><td>Int32</td></tr></table>

### <a href=#yearName name="yearName">yearName</a>

The name of the year containing the period  
First included in: financialCommon/FiscalCalendarPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Year Name</td></tr><tr><td>description</td><td>The name of the year containing the period</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#yearOffset name="yearOffset">yearOffset</a>

The number of years this year is offset from the current year for use in computations such as prior year  
First included in: financialCommon/FiscalCalendarPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Year Offset</td></tr><tr><td>description</td><td>The number of years this year is offset from the current year for use in computations such as prior year</td></tr><tr><td>dataFormat</td><td>Int32</td></tr></table>

### <a href=#quarter name="quarter">quarter</a>

The name of the quarter containing the period  
First included in: financialCommon/FiscalCalendarPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quarter</td></tr><tr><td>description</td><td>The name of the quarter containing the period</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

### <a href=#quarterOffset name="quarterOffset">quarterOffset</a>

The number of quarters this quarter is offset from the current quarter for use in computations such as same quarter previous year  
First included in: financialCommon/FiscalCalendarPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quarter Offset</td></tr><tr><td>description</td><td>The number of quarters this quarter is offset from the current quarter for use in computations such as same quarter previous year</td></tr><tr><td>dataFormat</td><td>Int32</td></tr></table>

### <a href=#month name="month">month</a>

The month containing the period.  
First included in: financialCommon/FiscalCalendarPeriod (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Month</td></tr><tr><td>description</td><td>The month containing the period.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr></table>
