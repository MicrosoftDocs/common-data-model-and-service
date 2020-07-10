---
title: WorkflowEscalationPathEntity in Workflow - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Workflow escalation path in Workflow(WorkflowEscalationPathEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/System/Workflow/WorkflowEscalationPathEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Workflow escalation path</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Level](#Level)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[StepId](#StepId)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[WorkflowUserValue](#WorkflowUserValue)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[AssignmentRelationType](#AssignmentRelationType)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[AssignmentType](#AssignmentType)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[HierarchyFilterConditionId](#HierarchyFilterConditionId)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[HierarchyFilterType](#HierarchyFilterType)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[HierarchyProviderName](#HierarchyProviderName)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[HierarchyStopConditionId](#HierarchyStopConditionId)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[HierarchyTokenName](#HierarchyTokenName)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[ParticipantProviderName](#ParticipantProviderName)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[ParticipantTokenName](#ParticipantTokenName)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[QueueProviderName](#QueueProviderName)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[QueueTokenName](#QueueTokenName)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[UserValue](#UserValue)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[DailyCalendar](#DailyCalendar)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[DailyCalendarProvider](#DailyCalendarProvider)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[DailyIncludeFriday](#DailyIncludeFriday)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[DailyIncludeMonday](#DailyIncludeMonday)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[DailyIncludeSaturday](#DailyIncludeSaturday)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[DailyIncludeSunday](#DailyIncludeSunday)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[DailyIncludeThursday](#DailyIncludeThursday)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[DailyIncludeTuesday](#DailyIncludeTuesday)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[DailyIncludeWednesday](#DailyIncludeWednesday)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[DailyUseNonCalendar](#DailyUseNonCalendar)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[DailyValue](#DailyValue)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[DateType](#DateType)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[HourCalendar](#HourCalendar)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[HourCalendarProvider](#HourCalendarProvider)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[HourIncludeFriday](#HourIncludeFriday)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[HourIncludeMonday](#HourIncludeMonday)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[HourIncludeSaturday](#HourIncludeSaturday)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[HourIncludeSunday](#HourIncludeSunday)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[HourIncludeThursday](#HourIncludeThursday)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[HourIncludeTuesday](#HourIncludeTuesday)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[HourIncludeWednesday](#HourIncludeWednesday)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[HoursAvailable](#HoursAvailable)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[HourStartTime](#HourStartTime)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[HourUseNonCalendar](#HourUseNonCalendar)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[HourValue](#HourValue)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[MonthlyDayOfWeek](#MonthlyDayOfWeek)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[MonthlyWeekInMonth](#MonthlyWeekInMonth)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[TimeSpanRelationType](#TimeSpanRelationType)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[WeeklyDayOfWeek](#WeeklyDayOfWeek)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[WeeklyValue](#WeeklyValue)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[YearlyDayOfWeek](#YearlyDayOfWeek)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[YearlyMonthInYear](#YearlyMonthInYear)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[YearlyWeekInMonth](#YearlyWeekInMonth)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[Relationship_WorkflowStepRelationshipId](#Relationship_WorkflowStepRelationshipId)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[Relationship_HierarchyFilterConditionRelationshipId](#Relationship_HierarchyFilterConditionRelationshipId)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[Relationship_HierarchyStopConditionRelationshipId](#Relationship_HierarchyStopConditionRelationshipId)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|
|[BackingTable_WorkflowEscalationPathTableRelationshipId](#BackingTable_WorkflowEscalationPathTableRelationshipId)||<a href="WorkflowEscalationPathEntity.md" target="_blank">Workflow/WorkflowEscalationPathEntity</a>|

### <a href=#Level name="Level">Level</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StepId name="StepId">StepId</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StepId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowUserValue name="WorkflowUserValue">WorkflowUserValue</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowUserValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssignmentRelationType name="AssignmentRelationType">AssignmentRelationType</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssignmentRelationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssignmentType name="AssignmentType">AssignmentType</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssignmentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyFilterConditionId name="HierarchyFilterConditionId">HierarchyFilterConditionId</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyFilterConditionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyFilterType name="HierarchyFilterType">HierarchyFilterType</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyFilterType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyProviderName name="HierarchyProviderName">HierarchyProviderName</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyProviderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyStopConditionId name="HierarchyStopConditionId">HierarchyStopConditionId</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyStopConditionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyTokenName name="HierarchyTokenName">HierarchyTokenName</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyTokenName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParticipantProviderName name="ParticipantProviderName">ParticipantProviderName</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParticipantProviderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParticipantTokenName name="ParticipantTokenName">ParticipantTokenName</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParticipantTokenName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QueueProviderName name="QueueProviderName">QueueProviderName</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QueueProviderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QueueTokenName name="QueueTokenName">QueueTokenName</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QueueTokenName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserValue name="UserValue">UserValue</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyCalendar name="DailyCalendar">DailyCalendar</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

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

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

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

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeFriday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyIncludeMonday name="DailyIncludeMonday">DailyIncludeMonday</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeMonday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyIncludeSaturday name="DailyIncludeSaturday">DailyIncludeSaturday</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeSaturday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyIncludeSunday name="DailyIncludeSunday">DailyIncludeSunday</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeSunday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyIncludeThursday name="DailyIncludeThursday">DailyIncludeThursday</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeThursday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyIncludeTuesday name="DailyIncludeTuesday">DailyIncludeTuesday</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeTuesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyIncludeWednesday name="DailyIncludeWednesday">DailyIncludeWednesday</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeWednesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyUseNonCalendar name="DailyUseNonCalendar">DailyUseNonCalendar</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyUseNonCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyValue name="DailyValue">DailyValue</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateType name="DateType">DateType</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourCalendar name="HourCalendar">HourCalendar</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

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

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

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

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeFriday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourIncludeMonday name="HourIncludeMonday">HourIncludeMonday</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeMonday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourIncludeSaturday name="HourIncludeSaturday">HourIncludeSaturday</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeSaturday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourIncludeSunday name="HourIncludeSunday">HourIncludeSunday</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeSunday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourIncludeThursday name="HourIncludeThursday">HourIncludeThursday</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeThursday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourIncludeTuesday name="HourIncludeTuesday">HourIncludeTuesday</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeTuesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourIncludeWednesday name="HourIncludeWednesday">HourIncludeWednesday</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeWednesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HoursAvailable name="HoursAvailable">HoursAvailable</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HoursAvailable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourStartTime name="HourStartTime">HourStartTime</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourStartTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourUseNonCalendar name="HourUseNonCalendar">HourUseNonCalendar</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourUseNonCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourValue name="HourValue">HourValue</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MonthlyDayOfWeek name="MonthlyDayOfWeek">MonthlyDayOfWeek</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MonthlyDayOfWeek attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MonthlyWeekInMonth name="MonthlyWeekInMonth">MonthlyWeekInMonth</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MonthlyWeekInMonth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeSpanRelationType name="TimeSpanRelationType">TimeSpanRelationType</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeSpanRelationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WeeklyDayOfWeek name="WeeklyDayOfWeek">WeeklyDayOfWeek</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WeeklyDayOfWeek attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WeeklyValue name="WeeklyValue">WeeklyValue</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WeeklyValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#YearlyDayOfWeek name="YearlyDayOfWeek">YearlyDayOfWeek</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YearlyDayOfWeek attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#YearlyMonthInYear name="YearlyMonthInYear">YearlyMonthInYear</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YearlyMonthInYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#YearlyWeekInMonth name="YearlyWeekInMonth">YearlyWeekInMonth</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YearlyWeekInMonth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkflowStepRelationshipId name="Relationship_WorkflowStepRelationshipId">Relationship_WorkflowStepRelationshipId</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkflowStepRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HierarchyFilterConditionRelationshipId name="Relationship_HierarchyFilterConditionRelationshipId">Relationship_HierarchyFilterConditionRelationshipId</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HierarchyFilterConditionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HierarchyStopConditionRelationshipId name="Relationship_HierarchyStopConditionRelationshipId">Relationship_HierarchyStopConditionRelationshipId</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HierarchyStopConditionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WorkflowEscalationPathTableRelationshipId name="BackingTable_WorkflowEscalationPathTableRelationshipId">BackingTable_WorkflowEscalationPathTableRelationshipId</a>

First included in: Workflow/WorkflowEscalationPathEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WorkflowEscalationPathTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/System/Workflow/Framework/WorkflowEscalationPathTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowEscalationPathTable.cdm.json/WorkflowEscalationPathTable</a></td><td><a href="../../../Tables/System/Workflow/Framework/WorkflowEscalationPathTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
