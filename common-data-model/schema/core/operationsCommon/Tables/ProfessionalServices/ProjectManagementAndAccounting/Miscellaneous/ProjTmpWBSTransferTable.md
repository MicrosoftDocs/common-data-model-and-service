---
title: ProjTmpWBSTransferTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# ProjTmpWBSTransferTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Miscellaneous/ProjTmpWBSTransferTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProjTmpWBSTransferTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ProjTmpWBSTransferTable.md" target="_blank">Miscellaneous/ProjTmpWBSTransferTable</a>|
|[ActivityDuration](#ActivityDuration)||<a href="ProjTmpWBSTransferTable.md" target="_blank">Miscellaneous/ProjTmpWBSTransferTable</a>|
|[ActivityNumber](#ActivityNumber)||<a href="ProjTmpWBSTransferTable.md" target="_blank">Miscellaneous/ProjTmpWBSTransferTable</a>|
|[CostAtComplete](#CostAtComplete)||<a href="ProjTmpWBSTransferTable.md" target="_blank">Miscellaneous/ProjTmpWBSTransferTable</a>|
|[Effort](#Effort)||<a href="ProjTmpWBSTransferTable.md" target="_blank">Miscellaneous/ProjTmpWBSTransferTable</a>|
|[EffortAtComplete](#EffortAtComplete)||<a href="ProjTmpWBSTransferTable.md" target="_blank">Miscellaneous/ProjTmpWBSTransferTable</a>|
|[ElementNumber](#ElementNumber)||<a href="ProjTmpWBSTransferTable.md" target="_blank">Miscellaneous/ProjTmpWBSTransferTable</a>|
|[HierarchyId](#HierarchyId)||<a href="ProjTmpWBSTransferTable.md" target="_blank">Miscellaneous/ProjTmpWBSTransferTable</a>|
|[Level](#Level)||<a href="ProjTmpWBSTransferTable.md" target="_blank">Miscellaneous/ProjTmpWBSTransferTable</a>|
|[Path](#Path)||<a href="ProjTmpWBSTransferTable.md" target="_blank">Miscellaneous/ProjTmpWBSTransferTable</a>|
|[PSASchedEnd](#PSASchedEnd)||<a href="ProjTmpWBSTransferTable.md" target="_blank">Miscellaneous/ProjTmpWBSTransferTable</a>|
|[PSASchedStart](#PSASchedStart)||<a href="ProjTmpWBSTransferTable.md" target="_blank">Miscellaneous/ProjTmpWBSTransferTable</a>|
|[SiblingNumber](#SiblingNumber)||<a href="ProjTmpWBSTransferTable.md" target="_blank">Miscellaneous/ProjTmpWBSTransferTable</a>|
|[DataAreaId](#DataAreaId)||<a href="ProjTmpWBSTransferTable.md" target="_blank">Miscellaneous/ProjTmpWBSTransferTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ProjTmpWBSTransferTable.md" target="_blank">Miscellaneous/ProjTmpWBSTransferTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/ProjTmpWBSTransferTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProjTmpWBSTransferTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ActivityDuration name="ActivityDuration">ActivityDuration</a>

First included in: Miscellaneous/ProjTmpWBSTransferTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityDuration attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ActivityNumber name="ActivityNumber">ActivityNumber</a>

First included in: Miscellaneous/ProjTmpWBSTransferTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostAtComplete name="CostAtComplete">CostAtComplete</a>

First included in: Miscellaneous/ProjTmpWBSTransferTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAtComplete attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Effort name="Effort">Effort</a>

First included in: Miscellaneous/ProjTmpWBSTransferTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Effort attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EffortAtComplete name="EffortAtComplete">EffortAtComplete</a>

First included in: Miscellaneous/ProjTmpWBSTransferTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffortAtComplete attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ElementNumber name="ElementNumber">ElementNumber</a>

First included in: Miscellaneous/ProjTmpWBSTransferTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyId name="HierarchyId">HierarchyId</a>

First included in: Miscellaneous/ProjTmpWBSTransferTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Level name="Level">Level</a>

First included in: Miscellaneous/ProjTmpWBSTransferTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Path name="Path">Path</a>

First included in: Miscellaneous/ProjTmpWBSTransferTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Path attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSASchedEnd name="PSASchedEnd">PSASchedEnd</a>

First included in: Miscellaneous/ProjTmpWBSTransferTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSASchedEnd attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PSASchedStart name="PSASchedStart">PSASchedStart</a>

First included in: Miscellaneous/ProjTmpWBSTransferTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSASchedStart attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#SiblingNumber name="SiblingNumber">SiblingNumber</a>

First included in: Miscellaneous/ProjTmpWBSTransferTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiblingNumber attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/ProjTmpWBSTransferTable (this entity)  

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/ProjTmpWBSTransferTable (this entity)  

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
