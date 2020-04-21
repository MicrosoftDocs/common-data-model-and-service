---
title: JmgIndirectTimeAndAttendanceActivityEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# JmgIndirectTimeAndAttendanceActivityEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[ActivityId](#ActivityId)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|
|[BreakCancelationRule](#BreakCancelationRule)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|
|[IsBreakPayable](#IsBreakPayable)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|
|[BreakDurationMinutes](#BreakDurationMinutes)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|
|[BreakToleranceMinutes](#BreakToleranceMinutes)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|
|[IndirectTimeAndAttendanceCategoryId](#IndirectTimeAndAttendanceCategoryId)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|
|[ActivityDescription](#ActivityDescription)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|
|[IsSwitchCodeApprovalRequired](#IsSwitchCodeApprovalRequired)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|
|[TimeAndAttendanceJobId](#TimeAndAttendanceJobId)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|
|[MainAccountId](#MainAccountId)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|
|[OffsetAccountId](#OffsetAccountId)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|
|[IsWorkerRegistrationAllowed](#IsWorkerRegistrationAllowed)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|
|[JobSystemFunction](#JobSystemFunction)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|
|[MainAccountIdDisplayValue](#MainAccountIdDisplayValue)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|
|[OffsetAccountIdDisplayValue](#OffsetAccountIdDisplayValue)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|
|[Relationship_LedgerDimensionCombinationRelationshipId](#Relationship_LedgerDimensionCombinationRelationshipId)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|
|[Relationship_OffsetLedgerDimensionCombinationRelationshipId](#Relationship_OffsetLedgerDimensionCombinationRelationshipId)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|
|[BackingTable_JmgIpcActivityRelationshipId](#BackingTable_JmgIpcActivityRelationshipId)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JmgIndirectTimeAndAttendanceActivityEntity.md" target="_blank">ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity</a>|

### <a href=#ActivityId name="ActivityId">ActivityId</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BreakCancelationRule name="BreakCancelationRule">BreakCancelationRule</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BreakCancelationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBreakPayable name="IsBreakPayable">IsBreakPayable</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBreakPayable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BreakDurationMinutes name="BreakDurationMinutes">BreakDurationMinutes</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BreakDurationMinutes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BreakToleranceMinutes name="BreakToleranceMinutes">BreakToleranceMinutes</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BreakToleranceMinutes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IndirectTimeAndAttendanceCategoryId name="IndirectTimeAndAttendanceCategoryId">IndirectTimeAndAttendanceCategoryId</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndirectTimeAndAttendanceCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActivityDescription name="ActivityDescription">ActivityDescription</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSwitchCodeApprovalRequired name="IsSwitchCodeApprovalRequired">IsSwitchCodeApprovalRequired</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSwitchCodeApprovalRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeAndAttendanceJobId name="TimeAndAttendanceJobId">TimeAndAttendanceJobId</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeAndAttendanceJobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountId name="MainAccountId">MainAccountId</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetAccountId name="OffsetAccountId">OffsetAccountId</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkerRegistrationAllowed name="IsWorkerRegistrationAllowed">IsWorkerRegistrationAllowed</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkerRegistrationAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobSystemFunction name="JobSystemFunction">JobSystemFunction</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobSystemFunction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountIdDisplayValue name="MainAccountIdDisplayValue">MainAccountIdDisplayValue</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetAccountIdDisplayValue name="OffsetAccountIdDisplayValue">OffsetAccountIdDisplayValue</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerDimensionCombinationRelationshipId name="Relationship_LedgerDimensionCombinationRelationshipId">Relationship_LedgerDimensionCombinationRelationshipId</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OffsetLedgerDimensionCombinationRelationshipId name="Relationship_OffsetLedgerDimensionCombinationRelationshipId">Relationship_OffsetLedgerDimensionCombinationRelationshipId</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OffsetLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_JmgIpcActivityRelationshipId name="BackingTable_JmgIpcActivityRelationshipId">BackingTable_JmgIpcActivityRelationshipId</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JmgIpcActivityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Reference/JmgIpcActivity.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Reference/JmgIpcActivity.cdm.json/JmgIpcActivity</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Reference/JmgIpcActivity.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/JmgIndirectTimeAndAttendanceActivityEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
