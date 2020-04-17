---
title: DomainEventStateTransitionModel - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# DomainEventStateTransitionModel

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/AccountingFoundation/Miscellaneous/DomainEventStateTransitionModel.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DomainEventStateTransitionModel/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="DomainEventStateTransitionModel.md" target="_blank">Miscellaneous/DomainEventStateTransitionModel</a>|
|[CurrentEnumName](#CurrentEnumName)||<a href="DomainEventStateTransitionModel.md" target="_blank">Miscellaneous/DomainEventStateTransitionModel</a>|
|[CurrentEnumValueName](#CurrentEnumValueName)||<a href="DomainEventStateTransitionModel.md" target="_blank">Miscellaneous/DomainEventStateTransitionModel</a>|
|[NextEnumName](#NextEnumName)||<a href="DomainEventStateTransitionModel.md" target="_blank">Miscellaneous/DomainEventStateTransitionModel</a>|
|[NextEnumValueName](#NextEnumValueName)||<a href="DomainEventStateTransitionModel.md" target="_blank">Miscellaneous/DomainEventStateTransitionModel</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/DomainEventStateTransitionModel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DomainEventStateTransitionModel/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CurrentEnumName name="CurrentEnumName">CurrentEnumName</a>

First included in: Miscellaneous/DomainEventStateTransitionModel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentEnumName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrentEnumValueName name="CurrentEnumValueName">CurrentEnumValueName</a>

First included in: Miscellaneous/DomainEventStateTransitionModel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentEnumValueName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NextEnumName name="NextEnumName">NextEnumName</a>

First included in: Miscellaneous/DomainEventStateTransitionModel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NextEnumName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NextEnumValueName name="NextEnumValueName">NextEnumValueName</a>

First included in: Miscellaneous/DomainEventStateTransitionModel (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NextEnumValueName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
