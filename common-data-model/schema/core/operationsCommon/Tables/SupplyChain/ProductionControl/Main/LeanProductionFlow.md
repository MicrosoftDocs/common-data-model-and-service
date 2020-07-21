---
title: LeanProductionFlow in Main - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Production flows in Main(LeanProductionFlow)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductionControl/Main/LeanProductionFlow.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LeanProductionFlow/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Production flows</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LeanProductionFlow.md" target="_blank">Main/LeanProductionFlow</a>|
|[AverageTakt](#AverageTakt)||<a href="LeanProductionFlow.md" target="_blank">Main/LeanProductionFlow</a>|
|[MaximumTakt](#MaximumTakt)||<a href="LeanProductionFlow.md" target="_blank">Main/LeanProductionFlow</a>|
|[MinimumTakt](#MinimumTakt)||<a href="LeanProductionFlow.md" target="_blank">Main/LeanProductionFlow</a>|
|[PeriodForActualCycleTime](#PeriodForActualCycleTime)||<a href="LeanProductionFlow.md" target="_blank">Main/LeanProductionFlow</a>|
|[Plan](#Plan)||<a href="LeanProductionFlow.md" target="_blank">Main/LeanProductionFlow</a>|
|[ProductionFlowReference](#ProductionFlowReference)||<a href="LeanProductionFlow.md" target="_blank">Main/LeanProductionFlow</a>|
|[QuantityPerCycle](#QuantityPerCycle)||<a href="LeanProductionFlow.md" target="_blank">Main/LeanProductionFlow</a>|
|[QuantityPerCycleUnitOfMeasure](#QuantityPerCycleUnitOfMeasure)||<a href="LeanProductionFlow.md" target="_blank">Main/LeanProductionFlow</a>|
|[RequiredTakt](#RequiredTakt)||<a href="LeanProductionFlow.md" target="_blank">Main/LeanProductionFlow</a>|
|[TaktUnitOfMeasure](#TaktUnitOfMeasure)||<a href="LeanProductionFlow.md" target="_blank">Main/LeanProductionFlow</a>|
|[Relationship_LeanProductionFlowReferenceRelationshipId](#Relationship_LeanProductionFlowReferenceRelationshipId)||<a href="LeanProductionFlow.md" target="_blank">Main/LeanProductionFlow</a>|
|[Relationship_PlanRelationshipId](#Relationship_PlanRelationshipId)||<a href="LeanProductionFlow.md" target="_blank">Main/LeanProductionFlow</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/LeanProductionFlow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LeanProductionFlow/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AverageTakt name="AverageTakt">AverageTakt</a>

First included in: Main/LeanProductionFlow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AverageTakt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MaximumTakt name="MaximumTakt">MaximumTakt</a>

First included in: Main/LeanProductionFlow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumTakt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MinimumTakt name="MinimumTakt">MinimumTakt</a>

First included in: Main/LeanProductionFlow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumTakt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PeriodForActualCycleTime name="PeriodForActualCycleTime">PeriodForActualCycleTime</a>

First included in: Main/LeanProductionFlow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodForActualCycleTime attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Plan name="Plan">Plan</a>

First included in: Main/LeanProductionFlow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Plan attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProductionFlowReference name="ProductionFlowReference">ProductionFlowReference</a>

First included in: Main/LeanProductionFlow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionFlowReference attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#QuantityPerCycle name="QuantityPerCycle">QuantityPerCycle</a>

First included in: Main/LeanProductionFlow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantityPerCycle attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QuantityPerCycleUnitOfMeasure name="QuantityPerCycleUnitOfMeasure">QuantityPerCycleUnitOfMeasure</a>

First included in: Main/LeanProductionFlow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Per cycle unit of measure</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuantityPerCycleUnitOfMeasure attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Per cycle unit of measure</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RequiredTakt name="RequiredTakt">RequiredTakt</a>

First included in: Main/LeanProductionFlow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredTakt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaktUnitOfMeasure name="TaktUnitOfMeasure">TaktUnitOfMeasure</a>

First included in: Main/LeanProductionFlow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Takt unit</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaktUnitOfMeasure attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Takt unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_LeanProductionFlowReferenceRelationshipId name="Relationship_LeanProductionFlowReferenceRelationshipId">Relationship_LeanProductionFlowReferenceRelationshipId</a>

First included in: Main/LeanProductionFlow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LeanProductionFlowReferenceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LeanProductionFlowReference.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Main/LeanProductionFlowReference.cdm.json/LeanProductionFlowReference</a></td><td><a href="LeanProductionFlowReference.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PlanRelationshipId name="Relationship_PlanRelationshipId">Relationship_PlanRelationshipId</a>

First included in: Main/LeanProductionFlow (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PlanRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../MasterPlanning/Main/Plan.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Main/Plan.cdm.json/Plan</a></td><td><a href="../../MasterPlanning/Main/Plan.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
