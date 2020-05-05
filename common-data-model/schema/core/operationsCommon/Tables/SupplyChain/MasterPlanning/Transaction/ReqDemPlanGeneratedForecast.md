---
title: ReqDemPlanGeneratedForecast - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Demand forecast generation log

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Transaction/ReqDemPlanGeneratedForecast.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqDemPlanGeneratedForecast/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Demand forecast generation log</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ReqDemPlanGeneratedForecast.md" target="_blank">Transaction/ReqDemPlanGeneratedForecast</a>|
|[Comment](#Comment)||<a href="ReqDemPlanGeneratedForecast.md" target="_blank">Transaction/ReqDemPlanGeneratedForecast</a>|
|[DateGranularity](#DateGranularity)||<a href="ReqDemPlanGeneratedForecast.md" target="_blank">Transaction/ReqDemPlanGeneratedForecast</a>|
|[FilterQuery](#FilterQuery)||<a href="ReqDemPlanGeneratedForecast.md" target="_blank">Transaction/ReqDemPlanGeneratedForecast</a>|
|[ForecastHorizon](#ForecastHorizon)||<a href="ReqDemPlanGeneratedForecast.md" target="_blank">Transaction/ReqDemPlanGeneratedForecast</a>|
|[ForecastStartDate](#ForecastStartDate)||<a href="ReqDemPlanGeneratedForecast.md" target="_blank">Transaction/ReqDemPlanGeneratedForecast</a>|
|[FreezingHorizon](#FreezingHorizon)||<a href="ReqDemPlanGeneratedForecast.md" target="_blank">Transaction/ReqDemPlanGeneratedForecast</a>|
|[GeneratedByUser](#GeneratedByUser)||<a href="ReqDemPlanGeneratedForecast.md" target="_blank">Transaction/ReqDemPlanGeneratedForecast</a>|
|[HistoricalEnd](#HistoricalEnd)||<a href="ReqDemPlanGeneratedForecast.md" target="_blank">Transaction/ReqDemPlanGeneratedForecast</a>|
|[HistoricalStart](#HistoricalStart)||<a href="ReqDemPlanGeneratedForecast.md" target="_blank">Transaction/ReqDemPlanGeneratedForecast</a>|
|[LogType](#LogType)||<a href="ReqDemPlanGeneratedForecast.md" target="_blank">Transaction/ReqDemPlanGeneratedForecast</a>|
|[TaskCollection](#TaskCollection)||<a href="ReqDemPlanGeneratedForecast.md" target="_blank">Transaction/ReqDemPlanGeneratedForecast</a>|
|[Title](#Title)||<a href="ReqDemPlanGeneratedForecast.md" target="_blank">Transaction/ReqDemPlanGeneratedForecast</a>|
|[Relationship_ReqDemPlanTaskCollectionLogRelationshipId](#Relationship_ReqDemPlanTaskCollectionLogRelationshipId)||<a href="ReqDemPlanGeneratedForecast.md" target="_blank">Transaction/ReqDemPlanGeneratedForecast</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/ReqDemPlanGeneratedForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqDemPlanGeneratedForecast/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Comment name="Comment">Comment</a>

First included in: Transaction/ReqDemPlanGeneratedForecast (this entity)  

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

### <a href=#DateGranularity name="DateGranularity">DateGranularity</a>

First included in: Transaction/ReqDemPlanGeneratedForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateGranularity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#FilterQuery name="FilterQuery">FilterQuery</a>

First included in: Transaction/ReqDemPlanGeneratedForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FilterQuery attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastHorizon name="ForecastHorizon">ForecastHorizon</a>

First included in: Transaction/ReqDemPlanGeneratedForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastHorizon attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ForecastStartDate name="ForecastStartDate">ForecastStartDate</a>

First included in: Transaction/ReqDemPlanGeneratedForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastStartDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#FreezingHorizon name="FreezingHorizon">FreezingHorizon</a>

First included in: Transaction/ReqDemPlanGeneratedForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreezingHorizon attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#GeneratedByUser name="GeneratedByUser">GeneratedByUser</a>

First included in: Transaction/ReqDemPlanGeneratedForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Generated by</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneratedByUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Generated by</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HistoricalEnd name="HistoricalEnd">HistoricalEnd</a>

First included in: Transaction/ReqDemPlanGeneratedForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HistoricalEnd attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#HistoricalStart name="HistoricalStart">HistoricalStart</a>

First included in: Transaction/ReqDemPlanGeneratedForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HistoricalStart attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#LogType name="LogType">LogType</a>

First included in: Transaction/ReqDemPlanGeneratedForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaskCollection name="TaskCollection">TaskCollection</a>

First included in: Transaction/ReqDemPlanGeneratedForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaskCollection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Title name="Title">Title</a>

First included in: Transaction/ReqDemPlanGeneratedForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Title attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqDemPlanTaskCollectionLogRelationshipId name="Relationship_ReqDemPlanTaskCollectionLogRelationshipId">Relationship_ReqDemPlanTaskCollectionLogRelationshipId</a>

First included in: Transaction/ReqDemPlanGeneratedForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqDemPlanTaskCollectionLogRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../TransactionHeader/ReqDemPlanTaskCollectionLog.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/TransactionHeader/ReqDemPlanTaskCollectionLog.cdm.json/ReqDemPlanTaskCollectionLog</a></td><td><a href="../TransactionHeader/ReqDemPlanTaskCollectionLog.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
