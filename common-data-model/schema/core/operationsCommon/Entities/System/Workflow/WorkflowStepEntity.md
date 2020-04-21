---
title: WorkflowStepEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# WorkflowStepEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/System/Workflow/WorkflowStepEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CompletionPolicy](#CompletionPolicy)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[CompletionPolicyPercentage](#CompletionPolicyPercentage)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[ElementId](#ElementId)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[RunStep](#RunStep)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[RunStepConditionId](#RunStepConditionId)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[Name](#Name)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[Sequence](#Sequence)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[StepId](#StepId)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[WorkflowUserValue](#WorkflowUserValue)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[AssignmentRelationType](#AssignmentRelationType)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[AssignmentType](#AssignmentType)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[HierarchyFilterConditionId](#HierarchyFilterConditionId)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[HierarchyFilterType](#HierarchyFilterType)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[HierarchyProviderName](#HierarchyProviderName)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[HierarchyStopConditionId](#HierarchyStopConditionId)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[HierarchyTokenName](#HierarchyTokenName)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[ParticipantProviderName](#ParticipantProviderName)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[ParticipantTokenName](#ParticipantTokenName)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[QueueProviderName](#QueueProviderName)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[QueueTokenName](#QueueTokenName)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[UserValue](#UserValue)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[DailyCalendar](#DailyCalendar)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[DailyCalendarProvider](#DailyCalendarProvider)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[DailyIncludeFriday](#DailyIncludeFriday)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[DailyIncludeMonday](#DailyIncludeMonday)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[DailyIncludeSaturday](#DailyIncludeSaturday)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[DailyIncludeSunday](#DailyIncludeSunday)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[DailyIncludeThursday](#DailyIncludeThursday)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[DailyIncludeTuesday](#DailyIncludeTuesday)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[DailyIncludeWednesday](#DailyIncludeWednesday)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[DailyUseNonCalendar](#DailyUseNonCalendar)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[DailyValue](#DailyValue)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[DateType](#DateType)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[HourCalendar](#HourCalendar)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[HourCalendarProvider](#HourCalendarProvider)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[HourIncludeFriday](#HourIncludeFriday)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[HourIncludeMonday](#HourIncludeMonday)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[HourIncludeSaturday](#HourIncludeSaturday)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[HourIncludeSunday](#HourIncludeSunday)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[HourIncludeThursday](#HourIncludeThursday)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[HourIncludeTuesday](#HourIncludeTuesday)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[HourIncludeWednesday](#HourIncludeWednesday)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[HoursAvailable](#HoursAvailable)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[HourStartTime](#HourStartTime)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[HourUseNonCalendar](#HourUseNonCalendar)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[HourValue](#HourValue)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[MonthlyDayOfWeek](#MonthlyDayOfWeek)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[MonthlyWeekInMonth](#MonthlyWeekInMonth)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[TimeSpanRelationType](#TimeSpanRelationType)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[WeeklyDayOfWeek](#WeeklyDayOfWeek)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[WeeklyValue](#WeeklyValue)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[YearlyDayOfWeek](#YearlyDayOfWeek)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[YearlyMonthInYear](#YearlyMonthInYear)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[YearlyWeekInMonth](#YearlyWeekInMonth)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[EscalationAction](#EscalationAction)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[EscalationType](#EscalationType)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[EscalationPathAction](#EscalationPathAction)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[Relationship_WorkflowElementRelationshipId](#Relationship_WorkflowElementRelationshipId)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[Relationship_ConditionRelationshipId](#Relationship_ConditionRelationshipId)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[Relationship_HierarchyFilterConditionRelationshipId](#Relationship_HierarchyFilterConditionRelationshipId)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[Relationship_HierarchyStopConditionRelationshipId](#Relationship_HierarchyStopConditionRelationshipId)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|
|[BackingTable_WorkflowStepTableRelationshipId](#BackingTable_WorkflowStepTableRelationshipId)||<a href="WorkflowStepEntity.md" target="_blank">Workflow/WorkflowStepEntity</a>|

### <a href=#CompletionPolicy name="CompletionPolicy">CompletionPolicy</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompletionPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompletionPolicyPercentage name="CompletionPolicyPercentage">CompletionPolicyPercentage</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompletionPolicyPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElementId name="ElementId">ElementId</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RunStep name="RunStep">RunStep</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RunStep attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RunStepConditionId name="RunStepConditionId">RunStepConditionId</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RunStepConditionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Sequence name="Sequence">Sequence</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sequence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StepId name="StepId">StepId</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StepId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowUserValue name="WorkflowUserValue">WorkflowUserValue</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowUserValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssignmentRelationType name="AssignmentRelationType">AssignmentRelationType</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssignmentRelationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssignmentType name="AssignmentType">AssignmentType</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssignmentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyFilterConditionId name="HierarchyFilterConditionId">HierarchyFilterConditionId</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyFilterConditionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyFilterType name="HierarchyFilterType">HierarchyFilterType</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyFilterType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyProviderName name="HierarchyProviderName">HierarchyProviderName</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyProviderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyStopConditionId name="HierarchyStopConditionId">HierarchyStopConditionId</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyStopConditionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyTokenName name="HierarchyTokenName">HierarchyTokenName</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyTokenName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParticipantProviderName name="ParticipantProviderName">ParticipantProviderName</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParticipantProviderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParticipantTokenName name="ParticipantTokenName">ParticipantTokenName</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParticipantTokenName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QueueProviderName name="QueueProviderName">QueueProviderName</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QueueProviderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QueueTokenName name="QueueTokenName">QueueTokenName</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QueueTokenName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserValue name="UserValue">UserValue</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyCalendar name="DailyCalendar">DailyCalendar</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyCalendarProvider name="DailyCalendarProvider">DailyCalendarProvider</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyCalendarProvider attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyIncludeFriday name="DailyIncludeFriday">DailyIncludeFriday</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeFriday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyIncludeMonday name="DailyIncludeMonday">DailyIncludeMonday</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeMonday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyIncludeSaturday name="DailyIncludeSaturday">DailyIncludeSaturday</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeSaturday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyIncludeSunday name="DailyIncludeSunday">DailyIncludeSunday</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeSunday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyIncludeThursday name="DailyIncludeThursday">DailyIncludeThursday</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeThursday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyIncludeTuesday name="DailyIncludeTuesday">DailyIncludeTuesday</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeTuesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyIncludeWednesday name="DailyIncludeWednesday">DailyIncludeWednesday</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyIncludeWednesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyUseNonCalendar name="DailyUseNonCalendar">DailyUseNonCalendar</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyUseNonCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyValue name="DailyValue">DailyValue</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateType name="DateType">DateType</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourCalendar name="HourCalendar">HourCalendar</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourCalendarProvider name="HourCalendarProvider">HourCalendarProvider</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourCalendarProvider attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourIncludeFriday name="HourIncludeFriday">HourIncludeFriday</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeFriday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourIncludeMonday name="HourIncludeMonday">HourIncludeMonday</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeMonday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourIncludeSaturday name="HourIncludeSaturday">HourIncludeSaturday</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeSaturday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourIncludeSunday name="HourIncludeSunday">HourIncludeSunday</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeSunday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourIncludeThursday name="HourIncludeThursday">HourIncludeThursday</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeThursday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourIncludeTuesday name="HourIncludeTuesday">HourIncludeTuesday</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeTuesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourIncludeWednesday name="HourIncludeWednesday">HourIncludeWednesday</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourIncludeWednesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HoursAvailable name="HoursAvailable">HoursAvailable</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HoursAvailable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourStartTime name="HourStartTime">HourStartTime</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourStartTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourUseNonCalendar name="HourUseNonCalendar">HourUseNonCalendar</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourUseNonCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourValue name="HourValue">HourValue</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MonthlyDayOfWeek name="MonthlyDayOfWeek">MonthlyDayOfWeek</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MonthlyDayOfWeek attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MonthlyWeekInMonth name="MonthlyWeekInMonth">MonthlyWeekInMonth</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MonthlyWeekInMonth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeSpanRelationType name="TimeSpanRelationType">TimeSpanRelationType</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeSpanRelationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WeeklyDayOfWeek name="WeeklyDayOfWeek">WeeklyDayOfWeek</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WeeklyDayOfWeek attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WeeklyValue name="WeeklyValue">WeeklyValue</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WeeklyValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#YearlyDayOfWeek name="YearlyDayOfWeek">YearlyDayOfWeek</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YearlyDayOfWeek attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#YearlyMonthInYear name="YearlyMonthInYear">YearlyMonthInYear</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YearlyMonthInYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#YearlyWeekInMonth name="YearlyWeekInMonth">YearlyWeekInMonth</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YearlyWeekInMonth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EscalationAction name="EscalationAction">EscalationAction</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EscalationAction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EscalationType name="EscalationType">EscalationType</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EscalationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EscalationPathAction name="EscalationPathAction">EscalationPathAction</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EscalationPathAction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkflowElementRelationshipId name="Relationship_WorkflowElementRelationshipId">Relationship_WorkflowElementRelationshipId</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkflowElementRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ConditionRelationshipId name="Relationship_ConditionRelationshipId">Relationship_ConditionRelationshipId</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ConditionRelationshipId attribute are listed below.</summary>

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

First included in: Workflow/WorkflowStepEntity (this entity)  

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

First included in: Workflow/WorkflowStepEntity (this entity)  

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

### <a href=#BackingTable_WorkflowStepTableRelationshipId name="BackingTable_WorkflowStepTableRelationshipId">BackingTable_WorkflowStepTableRelationshipId</a>

First included in: Workflow/WorkflowStepEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WorkflowStepTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/System/Workflow/Framework/WorkflowStepTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowStepTable.cdm.json/WorkflowStepTable</a></td><td><a href="../../../Tables/System/Workflow/Framework/WorkflowStepTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
