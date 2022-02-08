---
title: LeanProductionFlowModelEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Lean production flow models in ProductionControl(LeanProductionFlowModelEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/LeanProductionFlowModelEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lean production flow models</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ModelName](#ModelName)||<a href="LeanProductionFlowModelEntity.md" target="_blank">ProductionControl/LeanProductionFlowModelEntity</a>|
|[ModelType](#ModelType)||<a href="LeanProductionFlowModelEntity.md" target="_blank">ProductionControl/LeanProductionFlowModelEntity</a>|
|[EPECycleDays](#EPECycleDays)||<a href="LeanProductionFlowModelEntity.md" target="_blank">ProductionControl/LeanProductionFlowModelEntity</a>|
|[PlanningPeriodType](#PlanningPeriodType)||<a href="LeanProductionFlowModelEntity.md" target="_blank">ProductionControl/LeanProductionFlowModelEntity</a>|
|[PlanningTimeFence](#PlanningTimeFence)||<a href="LeanProductionFlowModelEntity.md" target="_blank">ProductionControl/LeanProductionFlowModelEntity</a>|
|[CapacityShortageReaction](#CapacityShortageReaction)||<a href="LeanProductionFlowModelEntity.md" target="_blank">ProductionControl/LeanProductionFlowModelEntity</a>|
|[BackingTable_LeanProductionFlowModelRelationshipId](#BackingTable_LeanProductionFlowModelRelationshipId)||<a href="LeanProductionFlowModelEntity.md" target="_blank">ProductionControl/LeanProductionFlowModelEntity</a>|

### <a href=#ModelName name="ModelName">ModelName</a>

First included in: ProductionControl/LeanProductionFlowModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModelName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ModelType name="ModelType">ModelType</a>

First included in: ProductionControl/LeanProductionFlowModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModelType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EPECycleDays name="EPECycleDays">EPECycleDays</a>

First included in: ProductionControl/LeanProductionFlowModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPECycleDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlanningPeriodType name="PlanningPeriodType">PlanningPeriodType</a>

First included in: ProductionControl/LeanProductionFlowModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlanningPeriodType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlanningTimeFence name="PlanningTimeFence">PlanningTimeFence</a>

First included in: ProductionControl/LeanProductionFlowModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlanningTimeFence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CapacityShortageReaction name="CapacityShortageReaction">CapacityShortageReaction</a>

First included in: ProductionControl/LeanProductionFlowModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CapacityShortageReaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_LeanProductionFlowModelRelationshipId name="BackingTable_LeanProductionFlowModelRelationshipId">BackingTable_LeanProductionFlowModelRelationshipId</a>

First included in: ProductionControl/LeanProductionFlowModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LeanProductionFlowModelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Group/LeanProductionFlowModel.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/LeanProductionFlowModel.cdm.json/LeanProductionFlowModel</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Group/LeanProductionFlowModel.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
