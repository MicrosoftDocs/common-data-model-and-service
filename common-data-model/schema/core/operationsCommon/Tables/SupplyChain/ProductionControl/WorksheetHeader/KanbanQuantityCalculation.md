---
title: KanbanQuantityCalculation - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Kanban quantity calculations

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductionControl/WorksheetHeader/KanbanQuantityCalculation.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[KanbanQuantityCalculation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Kanban quantity calculations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="KanbanQuantityCalculation.md" target="_blank">WorksheetHeader/KanbanQuantityCalculation</a>|
|[CalculationStatus](#CalculationStatus)||<a href="KanbanQuantityCalculation.md" target="_blank">WorksheetHeader/KanbanQuantityCalculation</a>|
|[ExpectedDemandPeriodEnd](#ExpectedDemandPeriodEnd)||<a href="KanbanQuantityCalculation.md" target="_blank">WorksheetHeader/KanbanQuantityCalculation</a>|
|[ExpectedDemandPeriodStart](#ExpectedDemandPeriodStart)||<a href="KanbanQuantityCalculation.md" target="_blank">WorksheetHeader/KanbanQuantityCalculation</a>|
|[FulfilledDemandPeriodEnd](#FulfilledDemandPeriodEnd)||<a href="KanbanQuantityCalculation.md" target="_blank">WorksheetHeader/KanbanQuantityCalculation</a>|
|[FulfilledDemandPeriodStart](#FulfilledDemandPeriodStart)||<a href="KanbanQuantityCalculation.md" target="_blank">WorksheetHeader/KanbanQuantityCalculation</a>|
|[KanbanQuantityPolicy](#KanbanQuantityPolicy)||<a href="KanbanQuantityCalculation.md" target="_blank">WorksheetHeader/KanbanQuantityCalculation</a>|
|[KanbanRuleActiveAsOfDate](#KanbanRuleActiveAsOfDate)||<a href="KanbanQuantityCalculation.md" target="_blank">WorksheetHeader/KanbanQuantityCalculation</a>|
|[KanbanRuleNewValidFrom](#KanbanRuleNewValidFrom)||<a href="KanbanQuantityCalculation.md" target="_blank">WorksheetHeader/KanbanQuantityCalculation</a>|
|[Name](#Name)||<a href="KanbanQuantityCalculation.md" target="_blank">WorksheetHeader/KanbanQuantityCalculation</a>|
|[DataAreaId](#DataAreaId)||<a href="KanbanQuantityCalculation.md" target="_blank">WorksheetHeader/KanbanQuantityCalculation</a>|
|[Relationship_KanbanQuantityPolicyRelationshipId](#Relationship_KanbanQuantityPolicyRelationshipId)||<a href="KanbanQuantityCalculation.md" target="_blank">WorksheetHeader/KanbanQuantityCalculation</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="KanbanQuantityCalculation.md" target="_blank">WorksheetHeader/KanbanQuantityCalculation</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/KanbanQuantityCalculation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[KanbanQuantityCalculation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CalculationStatus name="CalculationStatus">CalculationStatus</a>

First included in: WorksheetHeader/KanbanQuantityCalculation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculationStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#ExpectedDemandPeriodEnd name="ExpectedDemandPeriodEnd">ExpectedDemandPeriodEnd</a>

First included in: WorksheetHeader/KanbanQuantityCalculation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpectedDemandPeriodEnd attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ExpectedDemandPeriodStart name="ExpectedDemandPeriodStart">ExpectedDemandPeriodStart</a>

First included in: WorksheetHeader/KanbanQuantityCalculation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpectedDemandPeriodStart attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#FulfilledDemandPeriodEnd name="FulfilledDemandPeriodEnd">FulfilledDemandPeriodEnd</a>

First included in: WorksheetHeader/KanbanQuantityCalculation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FulfilledDemandPeriodEnd attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#FulfilledDemandPeriodStart name="FulfilledDemandPeriodStart">FulfilledDemandPeriodStart</a>

First included in: WorksheetHeader/KanbanQuantityCalculation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FulfilledDemandPeriodStart attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#KanbanQuantityPolicy name="KanbanQuantityPolicy">KanbanQuantityPolicy</a>

First included in: WorksheetHeader/KanbanQuantityCalculation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Policy</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KanbanQuantityPolicy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Policy</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#KanbanRuleActiveAsOfDate name="KanbanRuleActiveAsOfDate">KanbanRuleActiveAsOfDate</a>

First included in: WorksheetHeader/KanbanQuantityCalculation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KanbanRuleActiveAsOfDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#KanbanRuleNewValidFrom name="KanbanRuleNewValidFrom">KanbanRuleNewValidFrom</a>

First included in: WorksheetHeader/KanbanQuantityCalculation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KanbanRuleNewValidFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: WorksheetHeader/KanbanQuantityCalculation (this entity)  

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

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/KanbanQuantityCalculation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_KanbanQuantityPolicyRelationshipId name="Relationship_KanbanQuantityPolicyRelationshipId">Relationship_KanbanQuantityPolicyRelationshipId</a>

First included in: WorksheetHeader/KanbanQuantityCalculation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_KanbanQuantityPolicyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/KanbanQuantityPolicy.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/KanbanQuantityPolicy.cdm.json/KanbanQuantityPolicy</a></td><td><a href="../Group/KanbanQuantityPolicy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/KanbanQuantityCalculation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
