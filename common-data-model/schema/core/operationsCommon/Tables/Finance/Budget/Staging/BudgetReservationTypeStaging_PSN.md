---
title: BudgetReservationTypeStaging_PSN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# BudgetReservationTypeStaging_PSN

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Budget/Staging/BudgetReservationTypeStaging_PSN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetReservationTypeStaging_PSN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BudgetReservationTypeStaging_PSN.md" target="_blank">Staging/BudgetReservationTypeStaging_PSN</a>|
|[DefinitionGroup](#DefinitionGroup)||<a href="BudgetReservationTypeStaging_PSN.md" target="_blank">Staging/BudgetReservationTypeStaging_PSN</a>|
|[ExecutionId](#ExecutionId)||<a href="BudgetReservationTypeStaging_PSN.md" target="_blank">Staging/BudgetReservationTypeStaging_PSN</a>|
|[IsSelected](#IsSelected)||<a href="BudgetReservationTypeStaging_PSN.md" target="_blank">Staging/BudgetReservationTypeStaging_PSN</a>|
|[TransferStatus](#TransferStatus)||<a href="BudgetReservationTypeStaging_PSN.md" target="_blank">Staging/BudgetReservationTypeStaging_PSN</a>|
|[Description](#Description)||<a href="BudgetReservationTypeStaging_PSN.md" target="_blank">Staging/BudgetReservationTypeStaging_PSN</a>|
|[ReservationType](#ReservationType)||<a href="BudgetReservationTypeStaging_PSN.md" target="_blank">Staging/BudgetReservationTypeStaging_PSN</a>|
|[NumberSequenceCode](#NumberSequenceCode)||<a href="BudgetReservationTypeStaging_PSN.md" target="_blank">Staging/BudgetReservationTypeStaging_PSN</a>|
|[ReduceCarryForwardBudget](#ReduceCarryForwardBudget)||<a href="BudgetReservationTypeStaging_PSN.md" target="_blank">Staging/BudgetReservationTypeStaging_PSN</a>|
|[RelievingDocument](#RelievingDocument)||<a href="BudgetReservationTypeStaging_PSN.md" target="_blank">Staging/BudgetReservationTypeStaging_PSN</a>|
|[Workflow](#Workflow)||<a href="BudgetReservationTypeStaging_PSN.md" target="_blank">Staging/BudgetReservationTypeStaging_PSN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Staging/BudgetReservationTypeStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetReservationTypeStaging_PSN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DefinitionGroup name="DefinitionGroup">DefinitionGroup</a>

First included in: Staging/BudgetReservationTypeStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefinitionGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExecutionId name="ExecutionId">ExecutionId</a>

First included in: Staging/BudgetReservationTypeStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExecutionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSelected name="IsSelected">IsSelected</a>

First included in: Staging/BudgetReservationTypeStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSelected attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransferStatus name="TransferStatus">TransferStatus</a>

First included in: Staging/BudgetReservationTypeStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Staging/BudgetReservationTypeStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReservationType name="ReservationType">ReservationType</a>

First included in: Staging/BudgetReservationTypeStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReservationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceCode name="NumberSequenceCode">NumberSequenceCode</a>

First included in: Staging/BudgetReservationTypeStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReduceCarryForwardBudget name="ReduceCarryForwardBudget">ReduceCarryForwardBudget</a>

First included in: Staging/BudgetReservationTypeStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReduceCarryForwardBudget attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RelievingDocument name="RelievingDocument">RelievingDocument</a>

First included in: Staging/BudgetReservationTypeStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RelievingDocument attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Workflow name="Workflow">Workflow</a>

First included in: Staging/BudgetReservationTypeStaging_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Workflow attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
