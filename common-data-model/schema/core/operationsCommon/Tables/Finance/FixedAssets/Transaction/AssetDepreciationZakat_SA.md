---
title: AssetDepreciationZakat_SA - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# AssetDepreciationZakat_SA

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FixedAssets/Transaction/AssetDepreciationZakat_SA.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetDepreciationZakat_SA/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AssetDepreciationZakat_SA.md" target="_blank">Transaction/AssetDepreciationZakat_SA</a>|
|[AssetGroup](#AssetGroup)||<a href="AssetDepreciationZakat_SA.md" target="_blank">Transaction/AssetDepreciationZakat_SA</a>|
|[CurrentYrGroupBalance](#CurrentYrGroupBalance)||<a href="AssetDepreciationZakat_SA.md" target="_blank">Transaction/AssetDepreciationZakat_SA</a>|
|[CurrentYrGroupValue](#CurrentYrGroupValue)||<a href="AssetDepreciationZakat_SA.md" target="_blank">Transaction/AssetDepreciationZakat_SA</a>|
|[DepreciationAsPerBooks](#DepreciationAsPerBooks)||<a href="AssetDepreciationZakat_SA.md" target="_blank">Transaction/AssetDepreciationZakat_SA</a>|
|[DepreciationDifference](#DepreciationDifference)||<a href="AssetDepreciationZakat_SA.md" target="_blank">Transaction/AssetDepreciationZakat_SA</a>|
|[DepreciationRatio](#DepreciationRatio)||<a href="AssetDepreciationZakat_SA.md" target="_blank">Transaction/AssetDepreciationZakat_SA</a>|
|[DepreciationValue](#DepreciationValue)||<a href="AssetDepreciationZakat_SA.md" target="_blank">Transaction/AssetDepreciationZakat_SA</a>|
|[GroupValueEndofYr](#GroupValueEndofYr)||<a href="AssetDepreciationZakat_SA.md" target="_blank">Transaction/AssetDepreciationZakat_SA</a>|
|[MaintenanceExpenses](#MaintenanceExpenses)||<a href="AssetDepreciationZakat_SA.md" target="_blank">Transaction/AssetDepreciationZakat_SA</a>|
|[PreviousYrCost](#PreviousYrCost)||<a href="AssetDepreciationZakat_SA.md" target="_blank">Transaction/AssetDepreciationZakat_SA</a>|
|[PreviousYrGrpValue](#PreviousYrGrpValue)||<a href="AssetDepreciationZakat_SA.md" target="_blank">Transaction/AssetDepreciationZakat_SA</a>|
|[Status](#Status)||<a href="AssetDepreciationZakat_SA.md" target="_blank">Transaction/AssetDepreciationZakat_SA</a>|
|[TotalCompensations](#TotalCompensations)||<a href="AssetDepreciationZakat_SA.md" target="_blank">Transaction/AssetDepreciationZakat_SA</a>|
|[Year](#Year)||<a href="AssetDepreciationZakat_SA.md" target="_blank">Transaction/AssetDepreciationZakat_SA</a>|
|[DataAreaId](#DataAreaId)||<a href="AssetDepreciationZakat_SA.md" target="_blank">Transaction/AssetDepreciationZakat_SA</a>|
|[Relationship_AssetGroupZakatRelationshipId](#Relationship_AssetGroupZakatRelationshipId)||<a href="AssetDepreciationZakat_SA.md" target="_blank">Transaction/AssetDepreciationZakat_SA</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AssetDepreciationZakat_SA.md" target="_blank">Transaction/AssetDepreciationZakat_SA</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/AssetDepreciationZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetDepreciationZakat_SA/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssetGroup name="AssetGroup">AssetGroup</a>

First included in: Transaction/AssetDepreciationZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CurrentYrGroupBalance name="CurrentYrGroupBalance">CurrentYrGroupBalance</a>

First included in: Transaction/AssetDepreciationZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentYrGroupBalance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CurrentYrGroupValue name="CurrentYrGroupValue">CurrentYrGroupValue</a>

First included in: Transaction/AssetDepreciationZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentYrGroupValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DepreciationAsPerBooks name="DepreciationAsPerBooks">DepreciationAsPerBooks</a>

First included in: Transaction/AssetDepreciationZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationAsPerBooks attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DepreciationDifference name="DepreciationDifference">DepreciationDifference</a>

First included in: Transaction/AssetDepreciationZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationDifference attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DepreciationRatio name="DepreciationRatio">DepreciationRatio</a>

First included in: Transaction/AssetDepreciationZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationRatio attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DepreciationValue name="DepreciationValue">DepreciationValue</a>

First included in: Transaction/AssetDepreciationZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#GroupValueEndofYr name="GroupValueEndofYr">GroupValueEndofYr</a>

First included in: Transaction/AssetDepreciationZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupValueEndofYr attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MaintenanceExpenses name="MaintenanceExpenses">MaintenanceExpenses</a>

First included in: Transaction/AssetDepreciationZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaintenanceExpenses attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PreviousYrCost name="PreviousYrCost">PreviousYrCost</a>

First included in: Transaction/AssetDepreciationZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreviousYrCost attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PreviousYrGrpValue name="PreviousYrGrpValue">PreviousYrGrpValue</a>

First included in: Transaction/AssetDepreciationZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreviousYrGrpValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Status name="Status">Status</a>

First included in: Transaction/AssetDepreciationZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TotalCompensations name="TotalCompensations">TotalCompensations</a>

First included in: Transaction/AssetDepreciationZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalCompensations attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Year name="Year">Year</a>

First included in: Transaction/AssetDepreciationZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Year attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/AssetDepreciationZakat_SA (this entity)  

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

### <a href=#Relationship_AssetGroupZakatRelationshipId name="Relationship_AssetGroupZakatRelationshipId">Relationship_AssetGroupZakatRelationshipId</a>

First included in: Transaction/AssetDepreciationZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetGroupZakatRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/AssetGroupZakat_SA.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Group/AssetGroupZakat_SA.cdm.json/AssetGroupZakat_SA</a></td><td><a href="../Group/AssetGroupZakat_SA.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/AssetDepreciationZakat_SA (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
