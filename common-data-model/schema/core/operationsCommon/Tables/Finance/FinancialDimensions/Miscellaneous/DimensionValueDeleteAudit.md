---
title: DimensionValueDeleteAudit - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# DimensionValueDeleteAudit

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FinancialDimensions/Miscellaneous/DimensionValueDeleteAudit.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DimensionValueDeleteAudit/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="DimensionValueDeleteAudit.md" target="_blank">Miscellaneous/DimensionValueDeleteAudit</a>|
|[EntityName](#EntityName)||<a href="DimensionValueDeleteAudit.md" target="_blank">Miscellaneous/DimensionValueDeleteAudit</a>|
|[RoleViewName](#RoleViewName)||<a href="DimensionValueDeleteAudit.md" target="_blank">Miscellaneous/DimensionValueDeleteAudit</a>|
|[EntityInstance](#EntityInstance)||<a href="DimensionValueDeleteAudit.md" target="_blank">Miscellaneous/DimensionValueDeleteAudit</a>|
|[EntityValue](#EntityValue)||<a href="DimensionValueDeleteAudit.md" target="_blank">Miscellaneous/DimensionValueDeleteAudit</a>|
|[DataArea](#DataArea)||<a href="DimensionValueDeleteAudit.md" target="_blank">Miscellaneous/DimensionValueDeleteAudit</a>|
|[EntityCategory](#EntityCategory)||<a href="DimensionValueDeleteAudit.md" target="_blank">Miscellaneous/DimensionValueDeleteAudit</a>|
|[IsDeleteAllowed](#IsDeleteAllowed)||<a href="DimensionValueDeleteAudit.md" target="_blank">Miscellaneous/DimensionValueDeleteAudit</a>|
|[Status](#Status)||<a href="DimensionValueDeleteAudit.md" target="_blank">Miscellaneous/DimensionValueDeleteAudit</a>|
|[StatusDetails](#StatusDetails)||<a href="DimensionValueDeleteAudit.md" target="_blank">Miscellaneous/DimensionValueDeleteAudit</a>|
|[CallStack](#CallStack)||<a href="DimensionValueDeleteAudit.md" target="_blank">Miscellaneous/DimensionValueDeleteAudit</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/DimensionValueDeleteAudit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DimensionValueDeleteAudit/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EntityName name="EntityName">EntityName</a>

First included in: Miscellaneous/DimensionValueDeleteAudit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntityName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoleViewName name="RoleViewName">RoleViewName</a>

First included in: Miscellaneous/DimensionValueDeleteAudit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoleViewName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntityInstance name="EntityInstance">EntityInstance</a>

First included in: Miscellaneous/DimensionValueDeleteAudit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntityInstance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EntityValue name="EntityValue">EntityValue</a>

First included in: Miscellaneous/DimensionValueDeleteAudit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntityValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataArea name="DataArea">DataArea</a>

First included in: Miscellaneous/DimensionValueDeleteAudit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntityCategory name="EntityCategory">EntityCategory</a>

First included in: Miscellaneous/DimensionValueDeleteAudit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntityCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsDeleteAllowed name="IsDeleteAllowed">IsDeleteAllowed</a>

First included in: Miscellaneous/DimensionValueDeleteAudit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeleteAllowed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Miscellaneous/DimensionValueDeleteAudit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StatusDetails name="StatusDetails">StatusDetails</a>

First included in: Miscellaneous/DimensionValueDeleteAudit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatusDetails attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CallStack name="CallStack">CallStack</a>

First included in: Miscellaneous/DimensionValueDeleteAudit (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CallStack attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
