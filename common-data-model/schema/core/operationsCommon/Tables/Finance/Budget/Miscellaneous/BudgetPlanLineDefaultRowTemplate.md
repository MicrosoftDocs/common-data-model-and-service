---
title: BudgetPlanLineDefaultRowTemplate in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Budget plan line default row template in Miscellaneous(BudgetPlanLineDefaultRowTemplate)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Budget/Miscellaneous/BudgetPlanLineDefaultRowTemplate.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetPlanLineDefaultRowTemplate/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget plan line default row template</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[Layout](#Layout)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[Process](#Process)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[Ordinal](#Ordinal)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[StartDate](#StartDate)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[EndDate](#EndDate)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[Scenario](#Scenario)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[EstimateType](#EstimateType)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[UnitOfMeasure](#UnitOfMeasure)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[BudgetClass](#BudgetClass)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[Comment](#Comment)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[IsNewRequest](#IsNewRequest)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[IsRecurring](#IsRecurring)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[AssetId](#AssetId)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[ProposedAsset](#ProposedAsset)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[ProposedProject](#ProposedProject)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[ProjectId](#ProjectId)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[Position](#Position)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[PositionScenario](#PositionScenario)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[TransactionCurrencyCode](#TransactionCurrencyCode)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[SourceDataAreaId](#SourceDataAreaId)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[BudgetClassDefaulted](#BudgetClassDefaulted)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[IsNewRequestDefaulted](#IsNewRequestDefaulted)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[IsRecurringDefaulted](#IsRecurringDefaulted)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[Relationship_LayoutRelationRelationshipId](#Relationship_LayoutRelationRelationshipId)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[Relationship_ProcessRelationshipId](#Relationship_ProcessRelationshipId)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[Relationship_ScenarioRelationshipId](#Relationship_ScenarioRelationshipId)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[Relationship_PositionRelationshipId](#Relationship_PositionRelationshipId)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[Relationship_PositionForecastScenarioRelationshipId](#Relationship_PositionForecastScenarioRelationshipId)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[Relationship_ProjectRelationshipId](#Relationship_ProjectRelationshipId)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[Relationship_ProposedAssetRelationshipId](#Relationship_ProposedAssetRelationshipId)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[Relationship_ProposedProjectRelationshipId](#Relationship_ProposedProjectRelationshipId)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[Relationship_AssetRelationshipId](#Relationship_AssetRelationshipId)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|
|[Relationship_TransactionCurrencyCodeRelationshipId](#Relationship_TransactionCurrencyCodeRelationshipId)||<a href="BudgetPlanLineDefaultRowTemplate.md" target="_blank">Miscellaneous/BudgetPlanLineDefaultRowTemplate</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetPlanLineDefaultRowTemplate/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Layout name="Layout">Layout</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Layout attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Process name="Process">Process</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Process attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Ordinal name="Ordinal">Ordinal</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ordinal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StartDate name="StartDate">StartDate</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#EndDate name="EndDate">EndDate</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Scenario name="Scenario">Scenario</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Scenario attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EstimateType name="EstimateType">EstimateType</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EstimateType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UnitOfMeasure name="UnitOfMeasure">UnitOfMeasure</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitOfMeasure attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetClass name="BudgetClass">BudgetClass</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetClass attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Comment name="Comment">Comment</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Comment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsNewRequest name="IsNewRequest">IsNewRequest</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsNewRequest attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsRecurring name="IsRecurring">IsRecurring</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRecurring attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AssetId name="AssetId">AssetId</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProposedAsset name="ProposedAsset">ProposedAsset</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProposedAsset attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProposedProject name="ProposedProject">ProposedProject</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProposedProject attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Position name="Position">Position</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Position attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PositionScenario name="PositionScenario">PositionScenario</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionScenario attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TransactionCurrencyCode name="TransactionCurrencyCode">TransactionCurrencyCode</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceDataAreaId name="SourceDataAreaId">SourceDataAreaId</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetClassDefaulted name="BudgetClassDefaulted">BudgetClassDefaulted</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetClassDefaulted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsNewRequestDefaulted name="IsNewRequestDefaulted">IsNewRequestDefaulted</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsNewRequestDefaulted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsRecurringDefaulted name="IsRecurringDefaulted">IsRecurringDefaulted</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRecurringDefaulted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Relationship_LayoutRelationRelationshipId name="Relationship_LayoutRelationRelationshipId">Relationship_LayoutRelationRelationshipId</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LayoutRelationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/BudgetPlanLayout.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanLayout.cdm.json/BudgetPlanLayout</a></td><td><a href="../Group/BudgetPlanLayout.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProcessRelationshipId name="Relationship_ProcessRelationshipId">Relationship_ProcessRelationshipId</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProcessRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/BudgetPlanningProcess.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanningProcess.cdm.json/BudgetPlanningProcess</a></td><td><a href="../Group/BudgetPlanningProcess.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ScenarioRelationshipId name="Relationship_ScenarioRelationshipId">Relationship_ScenarioRelationshipId</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ScenarioRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/BudgetPlanScenario.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanScenario.cdm.json/BudgetPlanScenario</a></td><td><a href="../Group/BudgetPlanScenario.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PositionRelationshipId name="Relationship_PositionRelationshipId">Relationship_PositionRelationshipId</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PositionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/HcmPositionForecast.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Main/HcmPositionForecast.cdm.json/HcmPositionForecast</a></td><td><a href="../Main/HcmPositionForecast.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PositionForecastScenarioRelationshipId name="Relationship_PositionForecastScenarioRelationshipId">Relationship_PositionForecastScenarioRelationshipId</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PositionForecastScenarioRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/HcmPositionForecastScenario.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/HcmPositionForecastScenario.cdm.json/HcmPositionForecastScenario</a></td><td><a href="../Group/HcmPositionForecastScenario.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjectRelationshipId name="Relationship_ProjectRelationshipId">Relationship_ProjectRelationshipId</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjectRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.cdm.json/ProjTable</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProposedAssetRelationshipId name="Relationship_ProposedAssetRelationshipId">Relationship_ProposedAssetRelationshipId</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProposedAssetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/BudgetPlanProposedAsset.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanProposedAsset.cdm.json/BudgetPlanProposedAsset</a></td><td><a href="../Group/BudgetPlanProposedAsset.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProposedProjectRelationshipId name="Relationship_ProposedProjectRelationshipId">Relationship_ProposedProjectRelationshipId</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProposedProjectRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/BudgetPlanProposedProject.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanProposedProject.cdm.json/BudgetPlanProposedProject</a></td><td><a href="../Group/BudgetPlanProposedProject.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetRelationshipId name="Relationship_AssetRelationshipId">Relationship_AssetRelationshipId</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FixedAssets/Main/AssetTable.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetTable.cdm.json/AssetTable</a></td><td><a href="../../FixedAssets/Main/AssetTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransactionCurrencyCodeRelationshipId name="Relationship_TransactionCurrencyCodeRelationshipId">Relationship_TransactionCurrencyCodeRelationshipId</a>

First included in: Miscellaneous/BudgetPlanLineDefaultRowTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransactionCurrencyCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
