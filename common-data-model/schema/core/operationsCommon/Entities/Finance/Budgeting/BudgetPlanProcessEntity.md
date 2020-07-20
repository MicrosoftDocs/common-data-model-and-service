---
title: BudgetPlanProcessEntity in Budgeting - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Budget plan process in Budgeting(BudgetPlanProcessEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Budgeting/BudgetPlanProcessEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget plan process</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ApprovalProcessState](#ApprovalProcessState)||<a href="BudgetPlanProcessEntity.md" target="_blank">Budgeting/BudgetPlanProcessEntity</a>|
|[BudgetCycleRecId](#BudgetCycleRecId)||<a href="BudgetPlanProcessEntity.md" target="_blank">Budgeting/BudgetPlanProcessEntity</a>|
|[Description](#Description)||<a href="BudgetPlanProcessEntity.md" target="_blank">Budgeting/BudgetPlanProcessEntity</a>|
|[LedgerRecId](#LedgerRecId)||<a href="BudgetPlanProcessEntity.md" target="_blank">Budgeting/BudgetPlanProcessEntity</a>|
|[Name](#Name)||<a href="BudgetPlanProcessEntity.md" target="_blank">Budgeting/BudgetPlanProcessEntity</a>|
|[OrganizationHierarchyTypeRecId](#OrganizationHierarchyTypeRecId)||<a href="BudgetPlanProcessEntity.md" target="_blank">Budgeting/BudgetPlanProcessEntity</a>|
|[AccountStructureRecId](#AccountStructureRecId)||<a href="BudgetPlanProcessEntity.md" target="_blank">Budgeting/BudgetPlanProcessEntity</a>|
|[BudgetCycleTimeSpanRecId](#BudgetCycleTimeSpanRecId)||<a href="BudgetPlanProcessEntity.md" target="_blank">Budgeting/BudgetPlanProcessEntity</a>|
|[BudgetCycle](#BudgetCycle)||<a href="BudgetPlanProcessEntity.md" target="_blank">Budgeting/BudgetPlanProcessEntity</a>|
|[BudgetCycleStartFiscalCalendarPeriod](#BudgetCycleStartFiscalCalendarPeriod)||<a href="BudgetPlanProcessEntity.md" target="_blank">Budgeting/BudgetPlanProcessEntity</a>|
|[BudgetCycleTimeSpanFiscalCalendar](#BudgetCycleTimeSpanFiscalCalendar)||<a href="BudgetPlanProcessEntity.md" target="_blank">Budgeting/BudgetPlanProcessEntity</a>|
|[BudgetCycleTimeSpan](#BudgetCycleTimeSpan)||<a href="BudgetPlanProcessEntity.md" target="_blank">Budgeting/BudgetPlanProcessEntity</a>|
|[FiscalCalendarId](#FiscalCalendarId)||<a href="BudgetPlanProcessEntity.md" target="_blank">Budgeting/BudgetPlanProcessEntity</a>|
|[Ledger](#Ledger)||<a href="BudgetPlanProcessEntity.md" target="_blank">Budgeting/BudgetPlanProcessEntity</a>|
|[OrganizationtHierarchyType](#OrganizationtHierarchyType)||<a href="BudgetPlanProcessEntity.md" target="_blank">Budgeting/BudgetPlanProcessEntity</a>|
|[AccountStructure](#AccountStructure)||<a href="BudgetPlanProcessEntity.md" target="_blank">Budgeting/BudgetPlanProcessEntity</a>|
|[BackingTable_BudgetPlanningProcessRelationshipId](#BackingTable_BudgetPlanningProcessRelationshipId)||<a href="BudgetPlanProcessEntity.md" target="_blank">Budgeting/BudgetPlanProcessEntity</a>|

### <a href=#ApprovalProcessState name="ApprovalProcessState">ApprovalProcessState</a>

First included in: Budgeting/BudgetPlanProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApprovalProcessState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetCycleRecId name="BudgetCycleRecId">BudgetCycleRecId</a>

First included in: Budgeting/BudgetPlanProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetCycleRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Budgeting/BudgetPlanProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerRecId name="LedgerRecId">LedgerRecId</a>

First included in: Budgeting/BudgetPlanProcessEntity (this entity)  

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

### <a href=#Name name="Name">Name</a>

First included in: Budgeting/BudgetPlanProcessEntity (this entity)  

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

### <a href=#OrganizationHierarchyTypeRecId name="OrganizationHierarchyTypeRecId">OrganizationHierarchyTypeRecId</a>

First included in: Budgeting/BudgetPlanProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationHierarchyTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructureRecId name="AccountStructureRecId">AccountStructureRecId</a>

First included in: Budgeting/BudgetPlanProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructureRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetCycleTimeSpanRecId name="BudgetCycleTimeSpanRecId">BudgetCycleTimeSpanRecId</a>

First included in: Budgeting/BudgetPlanProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetCycleTimeSpanRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetCycle name="BudgetCycle">BudgetCycle</a>

First included in: Budgeting/BudgetPlanProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetCycle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetCycleStartFiscalCalendarPeriod name="BudgetCycleStartFiscalCalendarPeriod">BudgetCycleStartFiscalCalendarPeriod</a>

First included in: Budgeting/BudgetPlanProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetCycleStartFiscalCalendarPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetCycleTimeSpanFiscalCalendar name="BudgetCycleTimeSpanFiscalCalendar">BudgetCycleTimeSpanFiscalCalendar</a>

First included in: Budgeting/BudgetPlanProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetCycleTimeSpanFiscalCalendar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetCycleTimeSpan name="BudgetCycleTimeSpan">BudgetCycleTimeSpan</a>

First included in: Budgeting/BudgetPlanProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetCycleTimeSpan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalCalendarId name="FiscalCalendarId">FiscalCalendarId</a>

First included in: Budgeting/BudgetPlanProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalCalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Ledger name="Ledger">Ledger</a>

First included in: Budgeting/BudgetPlanProcessEntity (this entity)  

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

### <a href=#OrganizationtHierarchyType name="OrganizationtHierarchyType">OrganizationtHierarchyType</a>

First included in: Budgeting/BudgetPlanProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationtHierarchyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructure name="AccountStructure">AccountStructure</a>

First included in: Budgeting/BudgetPlanProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BudgetPlanningProcessRelationshipId name="BackingTable_BudgetPlanningProcessRelationshipId">BackingTable_BudgetPlanningProcessRelationshipId</a>

First included in: Budgeting/BudgetPlanProcessEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BudgetPlanningProcessRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Budget/Group/BudgetPlanningProcess.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanningProcess.cdm.json/BudgetPlanningProcess</a></td><td><a href="../../../Tables/Finance/Budget/Group/BudgetPlanningProcess.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
