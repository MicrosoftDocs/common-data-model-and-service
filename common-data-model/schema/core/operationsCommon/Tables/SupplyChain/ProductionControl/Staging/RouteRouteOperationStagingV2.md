---
title: RouteRouteOperationStagingV2 in Staging - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Route operations V2 in Staging

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductionControl/Staging/RouteRouteOperationStagingV2.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RouteRouteOperationStagingV2/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Route operations V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RouteRouteOperationStagingV2.md" target="_blank">Staging/RouteRouteOperationStagingV2</a>|
|[NextOperationLinkType](#NextOperationLinkType)||<a href="RouteRouteOperationStagingV2.md" target="_blank">Staging/RouteRouteOperationStagingV2</a>|
|[DefinitionGroup](#DefinitionGroup)||<a href="RouteRouteOperationStagingV2.md" target="_blank">Staging/RouteRouteOperationStagingV2</a>|
|[ExecutionId](#ExecutionId)||<a href="RouteRouteOperationStagingV2.md" target="_blank">Staging/RouteRouteOperationStagingV2</a>|
|[IsSelected](#IsSelected)||<a href="RouteRouteOperationStagingV2.md" target="_blank">Staging/RouteRouteOperationStagingV2</a>|
|[TransferStatus](#TransferStatus)||<a href="RouteRouteOperationStagingV2.md" target="_blank">Staging/RouteRouteOperationStagingV2</a>|
|[AccumulatedScrapPercentage](#AccumulatedScrapPercentage)||<a href="RouteRouteOperationStagingV2.md" target="_blank">Staging/RouteRouteOperationStagingV2</a>|
|[NextRouteOperationNumber](#NextRouteOperationNumber)||<a href="RouteRouteOperationStagingV2.md" target="_blank">Staging/RouteRouteOperationStagingV2</a>|
|[OperationId](#OperationId)||<a href="RouteRouteOperationStagingV2.md" target="_blank">Staging/RouteRouteOperationStagingV2</a>|
|[OperationNumber](#OperationNumber)||<a href="RouteRouteOperationStagingV2.md" target="_blank">Staging/RouteRouteOperationStagingV2</a>|
|[OperationPriority](#OperationPriority)||<a href="RouteRouteOperationStagingV2.md" target="_blank">Staging/RouteRouteOperationStagingV2</a>|
|[RouteId](#RouteId)||<a href="RouteRouteOperationStagingV2.md" target="_blank">Staging/RouteRouteOperationStagingV2</a>|
|[ScrapPercentage](#ScrapPercentage)||<a href="RouteRouteOperationStagingV2.md" target="_blank">Staging/RouteRouteOperationStagingV2</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Staging/RouteRouteOperationStagingV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RouteRouteOperationStagingV2/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#NextOperationLinkType name="NextOperationLinkType">NextOperationLinkType</a>

First included in: Staging/RouteRouteOperationStagingV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NextOperationLinkType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DefinitionGroup name="DefinitionGroup">DefinitionGroup</a>

First included in: Staging/RouteRouteOperationStagingV2 (this entity)  

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

First included in: Staging/RouteRouteOperationStagingV2 (this entity)  

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

First included in: Staging/RouteRouteOperationStagingV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSelected attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TransferStatus name="TransferStatus">TransferStatus</a>

First included in: Staging/RouteRouteOperationStagingV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AccumulatedScrapPercentage name="AccumulatedScrapPercentage">AccumulatedScrapPercentage</a>

First included in: Staging/RouteRouteOperationStagingV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccumulatedScrapPercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NextRouteOperationNumber name="NextRouteOperationNumber">NextRouteOperationNumber</a>

First included in: Staging/RouteRouteOperationStagingV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NextRouteOperationNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#OperationId name="OperationId">OperationId</a>

First included in: Staging/RouteRouteOperationStagingV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationNumber name="OperationNumber">OperationNumber</a>

First included in: Staging/RouteRouteOperationStagingV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OperationPriority name="OperationPriority">OperationPriority</a>

First included in: Staging/RouteRouteOperationStagingV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationPriority attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RouteId name="RouteId">RouteId</a>

First included in: Staging/RouteRouteOperationStagingV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScrapPercentage name="ScrapPercentage">ScrapPercentage</a>

First included in: Staging/RouteRouteOperationStagingV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScrapPercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>
