---
title: BudgetPlanAllocationScheduleEntity in Budgeting - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Budget plan allocation schedules in Budgeting

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Budgeting/BudgetPlanAllocationScheduleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget plan allocation schedules</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AllocationMethod](#AllocationMethod)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[AllocationTerm](#AllocationTerm)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[BasisPlanScenario](#BasisPlanScenario)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[DestinationPlanScenario](#DestinationPlanScenario)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[Factor](#Factor)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[LedgerRecId](#LedgerRecId)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[PeriodKey](#PeriodKey)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[LedgerAllocationKeyDataAreaId](#LedgerAllocationKeyDataAreaId)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[AllocationRule](#AllocationRule)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[LedgerAllocationRuleDataAreaId](#LedgerAllocationRuleDataAreaId)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[AllocationSchedule](#AllocationSchedule)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[SourcePlanScenario](#SourcePlanScenario)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[UseSourceEffectiveDate](#UseSourceEffectiveDate)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[BasisScenario](#BasisScenario)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[BudgetAllocationTerm](#BudgetAllocationTerm)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[DestinationScenario](#DestinationScenario)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[Ledger](#Ledger)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[SourceScenario](#SourceScenario)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[AppendLines](#AppendLines)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|
|[BackingTable_BudgetPlanningAllocationScheduleRelationshipId](#BackingTable_BudgetPlanningAllocationScheduleRelationshipId)||<a href="BudgetPlanAllocationScheduleEntity.md" target="_blank">Budgeting/BudgetPlanAllocationScheduleEntity</a>|

### <a href=#AllocationMethod name="AllocationMethod">AllocationMethod</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllocationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllocationTerm name="AllocationTerm">AllocationTerm</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllocationTerm attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BasisPlanScenario name="BasisPlanScenario">BasisPlanScenario</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BasisPlanScenario attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationPlanScenario name="DestinationPlanScenario">DestinationPlanScenario</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationPlanScenario attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Factor name="Factor">Factor</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Factor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerRecId name="LedgerRecId">LedgerRecId</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodKey name="PeriodKey">PeriodKey</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerAllocationKeyDataAreaId name="LedgerAllocationKeyDataAreaId">LedgerAllocationKeyDataAreaId</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerAllocationKeyDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllocationRule name="AllocationRule">AllocationRule</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllocationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerAllocationRuleDataAreaId name="LedgerAllocationRuleDataAreaId">LedgerAllocationRuleDataAreaId</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerAllocationRuleDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllocationSchedule name="AllocationSchedule">AllocationSchedule</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllocationSchedule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourcePlanScenario name="SourcePlanScenario">SourcePlanScenario</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourcePlanScenario attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseSourceEffectiveDate name="UseSourceEffectiveDate">UseSourceEffectiveDate</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseSourceEffectiveDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BasisScenario name="BasisScenario">BasisScenario</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BasisScenario attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetAllocationTerm name="BudgetAllocationTerm">BudgetAllocationTerm</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetAllocationTerm attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationScenario name="DestinationScenario">DestinationScenario</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationScenario attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Ledger name="Ledger">Ledger</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ledger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceScenario name="SourceScenario">SourceScenario</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceScenario attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AppendLines name="AppendLines">AppendLines</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AppendLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BudgetPlanningAllocationScheduleRelationshipId name="BackingTable_BudgetPlanningAllocationScheduleRelationshipId">BackingTable_BudgetPlanningAllocationScheduleRelationshipId</a>

First included in: Budgeting/BudgetPlanAllocationScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BudgetPlanningAllocationScheduleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Budget/Group/BudgetPlanningAllocationSchedule.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanningAllocationSchedule.cdm.json/BudgetPlanningAllocationSchedule</a></td><td><a href="../../../Tables/Finance/Budget/Group/BudgetPlanningAllocationSchedule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
