---
title: WorkflowElementEntity in Workflow - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Workflow element in Workflow(WorkflowElementEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/System/Workflow/WorkflowElementEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Workflow element</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ConditionId](#ConditionId)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[AutoCompleteAction](#AutoCompleteAction)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[AutoCompleteConditionId](#AutoCompleteConditionId)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[WorkflowId](#WorkflowId)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[ElementId](#ElementId)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[ElementName](#ElementName)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[ElementType](#ElementType)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[EnableActionsInWorkList](#EnableActionsInWorkList)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[RunSubworkflow](#RunSubworkflow)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[RunSubworkflowConditionId](#RunSubworkflowConditionId)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[FinalApproverUser](#FinalApproverUser)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[Name](#Name)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[Required](#Required)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[RunInParallel](#RunInParallel)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[Sequence](#Sequence)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[EnableAutoComplete](#EnableAutoComplete)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[EnableFinalApprover](#EnableFinalApprover)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[EnableMaximumRuntime](#EnableMaximumRuntime)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeOutcome](#MaximumRuntimeOutcome)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeTime](#MaximumRuntimeTime)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeTimeZone](#MaximumRuntimeTimeZone)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[ParallelBranchName](#ParallelBranchName)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[ParallelBranchElementId](#ParallelBranchElementId)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeDailyCalendar](#MaximumRuntimeDailyCalendar)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeDailyCalendarProvider](#MaximumRuntimeDailyCalendarProvider)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeDailyIncludeFriday](#MaximumRuntimeDailyIncludeFriday)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeDailyIncludeMonday](#MaximumRuntimeDailyIncludeMonday)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeDailyIncludeSaturday](#MaximumRuntimeDailyIncludeSaturday)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeDailyIncludeSunday](#MaximumRuntimeDailyIncludeSunday)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeDailyIncludeThursday](#MaximumRuntimeDailyIncludeThursday)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeDailyIncludeTuesday](#MaximumRuntimeDailyIncludeTuesday)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeDailyIncludeWednesday](#MaximumRuntimeDailyIncludeWednesday)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeDailyUseNonCalendar](#MaximumRuntimeDailyUseNonCalendar)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeDailyValue](#MaximumRuntimeDailyValue)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeDateType](#MaximumRuntimeDateType)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeHourCalendar](#MaximumRuntimeHourCalendar)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeHourCalendarProvider](#MaximumRuntimeHourCalendarProvider)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeHourIncludeFriday](#MaximumRuntimeHourIncludeFriday)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeHourIncludeMonday](#MaximumRuntimeHourIncludeMonday)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeHourIncludeSaturday](#MaximumRuntimeHourIncludeSaturday)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeHourIncludeSunday](#MaximumRuntimeHourIncludeSunday)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeHourIncludeThursday](#MaximumRuntimeHourIncludeThursday)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeHourIncludeTuesday](#MaximumRuntimeHourIncludeTuesday)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeHourIncludeWednesday](#MaximumRuntimeHourIncludeWednesday)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeHoursAvailable](#MaximumRuntimeHoursAvailable)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeHourStartTime](#MaximumRuntimeHourStartTime)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeHourUseNonCalendar](#MaximumRuntimeHourUseNonCalendar)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeHourValue](#MaximumRuntimeHourValue)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeMonthlyDayOfWeek](#MaximumRuntimeMonthlyDayOfWeek)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeMonthlyWeekInMonth](#MaximumRuntimeMonthlyWeekInMonth)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeTimeSpanRelationType](#MaximumRuntimeTimeSpanRelationType)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeWeeklyDayOfWeek](#MaximumRuntimeWeeklyDayOfWeek)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeWeeklyValue](#MaximumRuntimeWeeklyValue)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeYearlyDayOfWeek](#MaximumRuntimeYearlyDayOfWeek)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeYearlyMonthInYear](#MaximumRuntimeYearlyMonthInYear)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[MaximumRuntimeYearlyWeekInMonth](#MaximumRuntimeYearlyWeekInMonth)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[Relationship_WorkflowVersionRelationshipId](#Relationship_WorkflowVersionRelationshipId)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[Relationship_ParallelBranchRelationshipId](#Relationship_ParallelBranchRelationshipId)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[Relationship_SubworkflowConditionRelationshipId](#Relationship_SubworkflowConditionRelationshipId)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[Relationship_AutoCompleteConditionRelationshipId](#Relationship_AutoCompleteConditionRelationshipId)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[Relationship_ConditionalDecisionConditionRelationshipId](#Relationship_ConditionalDecisionConditionRelationshipId)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|
|[BackingTable_WorkflowElementTableRelationshipId](#BackingTable_WorkflowElementTableRelationshipId)||<a href="WorkflowElementEntity.md" target="_blank">Workflow/WorkflowElementEntity</a>|

### <a href=#ConditionId name="ConditionId">ConditionId</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConditionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutoCompleteAction name="AutoCompleteAction">AutoCompleteAction</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoCompleteAction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutoCompleteConditionId name="AutoCompleteConditionId">AutoCompleteConditionId</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoCompleteConditionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowId name="WorkflowId">WorkflowId</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElementId name="ElementId">ElementId</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

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

### <a href=#ElementName name="ElementName">ElementName</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElementName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElementType name="ElementType">ElementType</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElementType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableActionsInWorkList name="EnableActionsInWorkList">EnableActionsInWorkList</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableActionsInWorkList attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RunSubworkflow name="RunSubworkflow">RunSubworkflow</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RunSubworkflow attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RunSubworkflowConditionId name="RunSubworkflowConditionId">RunSubworkflowConditionId</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RunSubworkflowConditionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FinalApproverUser name="FinalApproverUser">FinalApproverUser</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinalApproverUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Required name="Required">Required</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Required attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RunInParallel name="RunInParallel">RunInParallel</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RunInParallel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Sequence name="Sequence">Sequence</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sequence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableAutoComplete name="EnableAutoComplete">EnableAutoComplete</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableAutoComplete attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableFinalApprover name="EnableFinalApprover">EnableFinalApprover</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableFinalApprover attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableMaximumRuntime name="EnableMaximumRuntime">EnableMaximumRuntime</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableMaximumRuntime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeOutcome name="MaximumRuntimeOutcome">MaximumRuntimeOutcome</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeOutcome attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeTime name="MaximumRuntimeTime">MaximumRuntimeTime</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeTimeZone name="MaximumRuntimeTimeZone">MaximumRuntimeTimeZone</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParallelBranchName name="ParallelBranchName">ParallelBranchName</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParallelBranchName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParallelBranchElementId name="ParallelBranchElementId">ParallelBranchElementId</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParallelBranchElementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeDailyCalendar name="MaximumRuntimeDailyCalendar">MaximumRuntimeDailyCalendar</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeDailyCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeDailyCalendarProvider name="MaximumRuntimeDailyCalendarProvider">MaximumRuntimeDailyCalendarProvider</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeDailyCalendarProvider attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeDailyIncludeFriday name="MaximumRuntimeDailyIncludeFriday">MaximumRuntimeDailyIncludeFriday</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeDailyIncludeFriday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeDailyIncludeMonday name="MaximumRuntimeDailyIncludeMonday">MaximumRuntimeDailyIncludeMonday</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeDailyIncludeMonday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeDailyIncludeSaturday name="MaximumRuntimeDailyIncludeSaturday">MaximumRuntimeDailyIncludeSaturday</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeDailyIncludeSaturday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeDailyIncludeSunday name="MaximumRuntimeDailyIncludeSunday">MaximumRuntimeDailyIncludeSunday</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeDailyIncludeSunday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeDailyIncludeThursday name="MaximumRuntimeDailyIncludeThursday">MaximumRuntimeDailyIncludeThursday</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeDailyIncludeThursday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeDailyIncludeTuesday name="MaximumRuntimeDailyIncludeTuesday">MaximumRuntimeDailyIncludeTuesday</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeDailyIncludeTuesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeDailyIncludeWednesday name="MaximumRuntimeDailyIncludeWednesday">MaximumRuntimeDailyIncludeWednesday</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeDailyIncludeWednesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeDailyUseNonCalendar name="MaximumRuntimeDailyUseNonCalendar">MaximumRuntimeDailyUseNonCalendar</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeDailyUseNonCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeDailyValue name="MaximumRuntimeDailyValue">MaximumRuntimeDailyValue</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeDailyValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeDateType name="MaximumRuntimeDateType">MaximumRuntimeDateType</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeDateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeHourCalendar name="MaximumRuntimeHourCalendar">MaximumRuntimeHourCalendar</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeHourCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeHourCalendarProvider name="MaximumRuntimeHourCalendarProvider">MaximumRuntimeHourCalendarProvider</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeHourCalendarProvider attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeHourIncludeFriday name="MaximumRuntimeHourIncludeFriday">MaximumRuntimeHourIncludeFriday</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeHourIncludeFriday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeHourIncludeMonday name="MaximumRuntimeHourIncludeMonday">MaximumRuntimeHourIncludeMonday</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeHourIncludeMonday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeHourIncludeSaturday name="MaximumRuntimeHourIncludeSaturday">MaximumRuntimeHourIncludeSaturday</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeHourIncludeSaturday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeHourIncludeSunday name="MaximumRuntimeHourIncludeSunday">MaximumRuntimeHourIncludeSunday</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeHourIncludeSunday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeHourIncludeThursday name="MaximumRuntimeHourIncludeThursday">MaximumRuntimeHourIncludeThursday</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeHourIncludeThursday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeHourIncludeTuesday name="MaximumRuntimeHourIncludeTuesday">MaximumRuntimeHourIncludeTuesday</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeHourIncludeTuesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeHourIncludeWednesday name="MaximumRuntimeHourIncludeWednesday">MaximumRuntimeHourIncludeWednesday</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeHourIncludeWednesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeHoursAvailable name="MaximumRuntimeHoursAvailable">MaximumRuntimeHoursAvailable</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeHoursAvailable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeHourStartTime name="MaximumRuntimeHourStartTime">MaximumRuntimeHourStartTime</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeHourStartTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeHourUseNonCalendar name="MaximumRuntimeHourUseNonCalendar">MaximumRuntimeHourUseNonCalendar</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeHourUseNonCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeHourValue name="MaximumRuntimeHourValue">MaximumRuntimeHourValue</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeHourValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeMonthlyDayOfWeek name="MaximumRuntimeMonthlyDayOfWeek">MaximumRuntimeMonthlyDayOfWeek</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeMonthlyDayOfWeek attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeMonthlyWeekInMonth name="MaximumRuntimeMonthlyWeekInMonth">MaximumRuntimeMonthlyWeekInMonth</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeMonthlyWeekInMonth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeTimeSpanRelationType name="MaximumRuntimeTimeSpanRelationType">MaximumRuntimeTimeSpanRelationType</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeTimeSpanRelationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeWeeklyDayOfWeek name="MaximumRuntimeWeeklyDayOfWeek">MaximumRuntimeWeeklyDayOfWeek</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeWeeklyDayOfWeek attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeWeeklyValue name="MaximumRuntimeWeeklyValue">MaximumRuntimeWeeklyValue</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeWeeklyValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeYearlyDayOfWeek name="MaximumRuntimeYearlyDayOfWeek">MaximumRuntimeYearlyDayOfWeek</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeYearlyDayOfWeek attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeYearlyMonthInYear name="MaximumRuntimeYearlyMonthInYear">MaximumRuntimeYearlyMonthInYear</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeYearlyMonthInYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRuntimeYearlyWeekInMonth name="MaximumRuntimeYearlyWeekInMonth">MaximumRuntimeYearlyWeekInMonth</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRuntimeYearlyWeekInMonth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkflowVersionRelationshipId name="Relationship_WorkflowVersionRelationshipId">Relationship_WorkflowVersionRelationshipId</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkflowVersionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ParallelBranchRelationshipId name="Relationship_ParallelBranchRelationshipId">Relationship_ParallelBranchRelationshipId</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ParallelBranchRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SubworkflowConditionRelationshipId name="Relationship_SubworkflowConditionRelationshipId">Relationship_SubworkflowConditionRelationshipId</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SubworkflowConditionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AutoCompleteConditionRelationshipId name="Relationship_AutoCompleteConditionRelationshipId">Relationship_AutoCompleteConditionRelationshipId</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AutoCompleteConditionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ConditionalDecisionConditionRelationshipId name="Relationship_ConditionalDecisionConditionRelationshipId">Relationship_ConditionalDecisionConditionRelationshipId</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ConditionalDecisionConditionRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WorkflowElementTableRelationshipId name="BackingTable_WorkflowElementTableRelationshipId">BackingTable_WorkflowElementTableRelationshipId</a>

First included in: Workflow/WorkflowElementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WorkflowElementTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/System/Workflow/Framework/WorkflowElementTable.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Framework/WorkflowElementTable.cdm.json/WorkflowElementTable</a></td><td><a href="../../../Tables/System/Workflow/Framework/WorkflowElementTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
