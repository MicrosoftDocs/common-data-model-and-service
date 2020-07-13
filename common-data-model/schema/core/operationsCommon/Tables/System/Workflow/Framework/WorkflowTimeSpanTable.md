---
title: WorkflowTimeSpanTable in Framework - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Time span in Framework(WorkflowTimeSpanTable)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowTimeSpanTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WorkflowTimeSpanTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time span</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[DailyCalendar](#DailyCalendar)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[DailyCalendarProvider](#DailyCalendarProvider)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[DailyIncludeFriday](#DailyIncludeFriday)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[DailyIncludeMonday](#DailyIncludeMonday)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[DailyIncludeSaturday](#DailyIncludeSaturday)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[DailyIncludeSunday](#DailyIncludeSunday)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[DailyIncludeThursday](#DailyIncludeThursday)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[DailyIncludeTuesday](#DailyIncludeTuesday)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[DailyIncludeWednesday](#DailyIncludeWednesday)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[DailyUseNonCalendar](#DailyUseNonCalendar)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[DailyValue](#DailyValue)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[DateType](#DateType)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[HourCalendar](#HourCalendar)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[HourCalendarProvider](#HourCalendarProvider)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[HourIncludeFriday](#HourIncludeFriday)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[HourIncludeMonday](#HourIncludeMonday)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[HourIncludeSaturday](#HourIncludeSaturday)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[HourIncludeSunday](#HourIncludeSunday)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[HourIncludeThursday](#HourIncludeThursday)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[HourIncludeTuesday](#HourIncludeTuesday)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[HourIncludeWednesday](#HourIncludeWednesday)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[HoursAvailable](#HoursAvailable)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[HourStartTime](#HourStartTime)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[HourUseNonCalendar](#HourUseNonCalendar)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[HourValue](#HourValue)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[MonthlyDayOfWeek](#MonthlyDayOfWeek)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[MonthlyWeekInMonth](#MonthlyWeekInMonth)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[TimeSpanRelationType](#TimeSpanRelationType)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[WeeklyDayOfWeek](#WeeklyDayOfWeek)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[WeeklyValue](#WeeklyValue)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[WorkflowEscalationPathTable](#WorkflowEscalationPathTable)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[WorkflowMaxRuntimeTable](#WorkflowMaxRuntimeTable)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[WorkflowStepTable](#WorkflowStepTable)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[YearlyDayOfWeek](#YearlyDayOfWeek)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[YearlyMonthInYear](#YearlyMonthInYear)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[YearlyWeekInMonth](#YearlyWeekInMonth)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[Relationship_WorkflowEscalationPathTableRelationshipId](#Relationship_WorkflowEscalationPathTableRelationshipId)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[Relationship_WorkflowMaxRuntimeTableRelationshipId](#Relationship_WorkflowMaxRuntimeTableRelationshipId)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|
|[Relationship_WorkflowStepTableRelationshipId](#Relationship_WorkflowStepTableRelationshipId)||<a href="WorkflowTimeSpanTable.md" target="_blank">Framework/WorkflowTimeSpanTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WorkflowTimeSpanTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DailyCalendar name="DailyCalendar">DailyCalendar</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyCalendarProvider name="DailyCalendarProvider">DailyCalendarProvider</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyCalendarProvider attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyIncludeFriday name="DailyIncludeFriday">DailyIncludeFriday</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeFriday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DailyIncludeMonday name="DailyIncludeMonday">DailyIncludeMonday</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeMonday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DailyIncludeSaturday name="DailyIncludeSaturday">DailyIncludeSaturday</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeSaturday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DailyIncludeSunday name="DailyIncludeSunday">DailyIncludeSunday</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeSunday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DailyIncludeThursday name="DailyIncludeThursday">DailyIncludeThursday</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeThursday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DailyIncludeTuesday name="DailyIncludeTuesday">DailyIncludeTuesday</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeTuesday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DailyIncludeWednesday name="DailyIncludeWednesday">DailyIncludeWednesday</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeWednesday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DailyUseNonCalendar name="DailyUseNonCalendar">DailyUseNonCalendar</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyUseNonCalendar attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DailyValue name="DailyValue">DailyValue</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DateType name="DateType">DateType</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#HourCalendar name="HourCalendar">HourCalendar</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourCalendarProvider name="HourCalendarProvider">HourCalendarProvider</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourCalendarProvider attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourIncludeFriday name="HourIncludeFriday">HourIncludeFriday</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeFriday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#HourIncludeMonday name="HourIncludeMonday">HourIncludeMonday</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeMonday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#HourIncludeSaturday name="HourIncludeSaturday">HourIncludeSaturday</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeSaturday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#HourIncludeSunday name="HourIncludeSunday">HourIncludeSunday</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeSunday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#HourIncludeThursday name="HourIncludeThursday">HourIncludeThursday</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeThursday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#HourIncludeTuesday name="HourIncludeTuesday">HourIncludeTuesday</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeTuesday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#HourIncludeWednesday name="HourIncludeWednesday">HourIncludeWednesday</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeWednesday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#HoursAvailable name="HoursAvailable">HoursAvailable</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HoursAvailable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#HourStartTime name="HourStartTime">HourStartTime</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourStartTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#HourUseNonCalendar name="HourUseNonCalendar">HourUseNonCalendar</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourUseNonCalendar attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#HourValue name="HourValue">HourValue</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MonthlyDayOfWeek name="MonthlyDayOfWeek">MonthlyDayOfWeek</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MonthlyDayOfWeek attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MonthlyWeekInMonth name="MonthlyWeekInMonth">MonthlyWeekInMonth</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MonthlyWeekInMonth attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TimeSpanRelationType name="TimeSpanRelationType">TimeSpanRelationType</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeSpanRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WeeklyDayOfWeek name="WeeklyDayOfWeek">WeeklyDayOfWeek</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WeeklyDayOfWeek attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WeeklyValue name="WeeklyValue">WeeklyValue</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WeeklyValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WorkflowEscalationPathTable name="WorkflowEscalationPathTable">WorkflowEscalationPathTable</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowEscalationPathTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WorkflowMaxRuntimeTable name="WorkflowMaxRuntimeTable">WorkflowMaxRuntimeTable</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowMaxRuntimeTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WorkflowStepTable name="WorkflowStepTable">WorkflowStepTable</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowStepTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#YearlyDayOfWeek name="YearlyDayOfWeek">YearlyDayOfWeek</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YearlyDayOfWeek attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#YearlyMonthInYear name="YearlyMonthInYear">YearlyMonthInYear</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YearlyMonthInYear attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#YearlyWeekInMonth name="YearlyWeekInMonth">YearlyWeekInMonth</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YearlyWeekInMonth attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Relationship_WorkflowEscalationPathTableRelationshipId name="Relationship_WorkflowEscalationPathTableRelationshipId">Relationship_WorkflowEscalationPathTableRelationshipId</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkflowEscalationPathTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WorkflowEscalationPathTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowEscalationPathTable.cdm.json/WorkflowEscalationPathTable</a></td><td><a href="WorkflowEscalationPathTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkflowMaxRuntimeTableRelationshipId name="Relationship_WorkflowMaxRuntimeTableRelationshipId">Relationship_WorkflowMaxRuntimeTableRelationshipId</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkflowMaxRuntimeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WorkflowMaxRuntimeTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowMaxRuntimeTable.cdm.json/WorkflowMaxRuntimeTable</a></td><td><a href="WorkflowMaxRuntimeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkflowStepTableRelationshipId name="Relationship_WorkflowStepTableRelationshipId">Relationship_WorkflowStepTableRelationshipId</a>

First included in: Framework/WorkflowTimeSpanTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkflowStepTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WorkflowStepTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowStepTable.cdm.json/WorkflowStepTable</a></td><td><a href="WorkflowStepTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
