---
title: AssetGroupDepBookSetup - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# AssetGroupDepBookSetup

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FixedAssets/Group/AssetGroupDepBookSetup.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetGroupDepBookSetup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AssetGroupDepBookSetup.md" target="_blank">Group/AssetGroupDepBookSetup</a>|
|[AssetGroupId](#AssetGroupId)||<a href="AssetGroupDepBookSetup.md" target="_blank">Group/AssetGroupDepBookSetup</a>|
|[DepreciationBookId](#DepreciationBookId)||<a href="AssetGroupDepBookSetup.md" target="_blank">Group/AssetGroupDepBookSetup</a>|
|[LifeTime](#LifeTime)||<a href="AssetGroupDepBookSetup.md" target="_blank">Group/AssetGroupDepBookSetup</a>|
|[Depreciation](#Depreciation)||<a href="AssetGroupDepBookSetup.md" target="_blank">Group/AssetGroupDepBookSetup</a>|
|[ServiceLife](#ServiceLife)||<a href="AssetGroupDepBookSetup.md" target="_blank">Group/AssetGroupDepBookSetup</a>|
|[DepreciationProfile](#DepreciationProfile)||<a href="AssetGroupDepBookSetup.md" target="_blank">Group/AssetGroupDepBookSetup</a>|
|[DepreciationConvention](#DepreciationConvention)||<a href="AssetGroupDepBookSetup.md" target="_blank">Group/AssetGroupDepBookSetup</a>|
|[DepreciationAltProfile](#DepreciationAltProfile)||<a href="AssetGroupDepBookSetup.md" target="_blank">Group/AssetGroupDepBookSetup</a>|
|[DepreciationExtProfile](#DepreciationExtProfile)||<a href="AssetGroupDepBookSetup.md" target="_blank">Group/AssetGroupDepBookSetup</a>|
|[AssetGroupDepreciation_IN](#AssetGroupDepreciation_IN)||<a href="AssetGroupDepBookSetup.md" target="_blank">Group/AssetGroupDepBookSetup</a>|
|[AllowableLimitForAccumulatedDepType_JP](#AllowableLimitForAccumulatedDepType_JP)||<a href="AssetGroupDepBookSetup.md" target="_blank">Group/AssetGroupDepBookSetup</a>|
|[DepreciationAcceleratedProfile_JP](#DepreciationAcceleratedProfile_JP)||<a href="AssetGroupDepBookSetup.md" target="_blank">Group/AssetGroupDepBookSetup</a>|
|[SpecialDepAllocationPeriods_JP](#SpecialDepAllocationPeriods_JP)||<a href="AssetGroupDepBookSetup.md" target="_blank">Group/AssetGroupDepBookSetup</a>|
|[SpecialDepAllocationUnit_JP](#SpecialDepAllocationUnit_JP)||<a href="AssetGroupDepBookSetup.md" target="_blank">Group/AssetGroupDepBookSetup</a>|
|[SpecialDepAllocationConvention_JP](#SpecialDepAllocationConvention_JP)||<a href="AssetGroupDepBookSetup.md" target="_blank">Group/AssetGroupDepBookSetup</a>|
|[DataAreaId](#DataAreaId)||<a href="AssetGroupDepBookSetup.md" target="_blank">Group/AssetGroupDepBookSetup</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AssetGroupDepBookSetup.md" target="_blank">Group/AssetGroupDepBookSetup</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/AssetGroupDepBookSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetGroupDepBookSetup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssetGroupId name="AssetGroupId">AssetGroupId</a>

First included in: Group/AssetGroupDepBookSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationBookId name="DepreciationBookId">DepreciationBookId</a>

First included in: Group/AssetGroupDepBookSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationBookId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LifeTime name="LifeTime">LifeTime</a>

First included in: Group/AssetGroupDepBookSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LifeTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Depreciation name="Depreciation">Depreciation</a>

First included in: Group/AssetGroupDepBookSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Depreciation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ServiceLife name="ServiceLife">ServiceLife</a>

First included in: Group/AssetGroupDepBookSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceLife attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DepreciationProfile name="DepreciationProfile">DepreciationProfile</a>

First included in: Group/AssetGroupDepBookSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationConvention name="DepreciationConvention">DepreciationConvention</a>

First included in: Group/AssetGroupDepBookSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationConvention attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DepreciationAltProfile name="DepreciationAltProfile">DepreciationAltProfile</a>

First included in: Group/AssetGroupDepBookSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationAltProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationExtProfile name="DepreciationExtProfile">DepreciationExtProfile</a>

First included in: Group/AssetGroupDepBookSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationExtProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetGroupDepreciation_IN name="AssetGroupDepreciation_IN">AssetGroupDepreciation_IN</a>

First included in: Group/AssetGroupDepBookSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetGroupDepreciation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowableLimitForAccumulatedDepType_JP name="AllowableLimitForAccumulatedDepType_JP">AllowableLimitForAccumulatedDepType_JP</a>

First included in: Group/AssetGroupDepBookSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowableLimitForAccumulatedDepType_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DepreciationAcceleratedProfile_JP name="DepreciationAcceleratedProfile_JP">DepreciationAcceleratedProfile_JP</a>

First included in: Group/AssetGroupDepBookSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationAcceleratedProfile_JP attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialDepAllocationPeriods_JP name="SpecialDepAllocationPeriods_JP">SpecialDepAllocationPeriods_JP</a>

First included in: Group/AssetGroupDepBookSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepAllocationPeriods_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SpecialDepAllocationUnit_JP name="SpecialDepAllocationUnit_JP">SpecialDepAllocationUnit_JP</a>

First included in: Group/AssetGroupDepBookSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepAllocationUnit_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SpecialDepAllocationConvention_JP name="SpecialDepAllocationConvention_JP">SpecialDepAllocationConvention_JP</a>

First included in: Group/AssetGroupDepBookSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepAllocationConvention_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/AssetGroupDepBookSetup (this entity)  

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

First included in: Group/AssetGroupDepBookSetup (this entity)  

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
