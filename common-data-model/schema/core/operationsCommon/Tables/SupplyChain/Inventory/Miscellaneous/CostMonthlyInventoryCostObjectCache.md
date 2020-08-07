---
title: CostMonthlyInventoryCostObjectCache in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Monthly inventory cost object cache in Miscellaneous(CostMonthlyInventoryCostObjectCache)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Miscellaneous/CostMonthlyInventoryCostObjectCache.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CostMonthlyInventoryCostObjectCache/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Monthly inventory cost object cache</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[TransDate](#TransDate)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[ItemId](#ItemId)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[ConfigId](#ConfigId)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[ColorId](#ColorId)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[SizeId](#SizeId)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[StyleId](#StyleId)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[VersionId](#VersionId)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[SiteId](#SiteId)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[CostOfProcuredMaterials](#CostOfProcuredMaterials)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[CostOfManufacturedMaterials](#CostOfManufacturedMaterials)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[CostOfDisposedMaterials](#CostOfDisposedMaterials)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[CostOfDisposedMaterialsInCounting](#CostOfDisposedMaterialsInCounting)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[CostOfConsumedMaterials](#CostOfConsumedMaterials)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[CostOfTransferedMaterials](#CostOfTransferedMaterials)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[CostOfSoldMaterials](#CostOfSoldMaterials)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[NetChange](#NetChange)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[EndingBalance](#EndingBalance)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[SysDataCacheContextId](#SysDataCacheContextId)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[DataAreaId](#DataAreaId)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="CostMonthlyInventoryCostObjectCache.md" target="_blank">Miscellaneous/CostMonthlyInventoryCostObjectCache</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CostMonthlyInventoryCostObjectCache/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfigId name="ConfigId">ConfigId</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfigId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColorId name="ColorId">ColorId</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SizeId name="SizeId">SizeId</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StyleId name="StyleId">StyleId</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionId name="VersionId">VersionId</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SiteId name="SiteId">SiteId</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostOfProcuredMaterials name="CostOfProcuredMaterials">CostOfProcuredMaterials</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostOfProcuredMaterials attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CostOfManufacturedMaterials name="CostOfManufacturedMaterials">CostOfManufacturedMaterials</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostOfManufacturedMaterials attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CostOfDisposedMaterials name="CostOfDisposedMaterials">CostOfDisposedMaterials</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostOfDisposedMaterials attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CostOfDisposedMaterialsInCounting name="CostOfDisposedMaterialsInCounting">CostOfDisposedMaterialsInCounting</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostOfDisposedMaterialsInCounting attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CostOfConsumedMaterials name="CostOfConsumedMaterials">CostOfConsumedMaterials</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostOfConsumedMaterials attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CostOfTransferedMaterials name="CostOfTransferedMaterials">CostOfTransferedMaterials</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostOfTransferedMaterials attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CostOfSoldMaterials name="CostOfSoldMaterials">CostOfSoldMaterials</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostOfSoldMaterials attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NetChange name="NetChange">NetChange</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetChange attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EndingBalance name="EndingBalance">EndingBalance</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndingBalance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SysDataCacheContextId name="SysDataCacheContextId">SysDataCacheContextId</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SysDataCacheContextId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

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

First included in: Miscellaneous/CostMonthlyInventoryCostObjectCache (this entity)  

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
