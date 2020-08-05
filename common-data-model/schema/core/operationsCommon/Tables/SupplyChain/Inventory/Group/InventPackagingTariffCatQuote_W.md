---
title: InventPackagingTariffCatQuote_W in Group - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Allocation by tariff categories quotes in Group(InventPackagingTariffCatQuote_W)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventPackagingTariffCatQuote_W.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventPackagingTariffCatQuote_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allocation by tariff categories quotes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventPackagingTariffCatQuote_W.md" target="_blank">Group/InventPackagingTariffCatQuote_W</a>|
|[PackagingTariffCatAlloc](#PackagingTariffCatAlloc)||<a href="InventPackagingTariffCatQuote_W.md" target="_blank">Group/InventPackagingTariffCatQuote_W</a>|
|[Percent](#Percent)||<a href="InventPackagingTariffCatQuote_W.md" target="_blank">Group/InventPackagingTariffCatQuote_W</a>|
|[TariffCategoryId](#TariffCategoryId)||<a href="InventPackagingTariffCatQuote_W.md" target="_blank">Group/InventPackagingTariffCatQuote_W</a>|
|[DataAreaId](#DataAreaId)||<a href="InventPackagingTariffCatQuote_W.md" target="_blank">Group/InventPackagingTariffCatQuote_W</a>|
|[Relationship_InventPackagingTariffCat_WRelationshipId](#Relationship_InventPackagingTariffCat_WRelationshipId)||<a href="InventPackagingTariffCatQuote_W.md" target="_blank">Group/InventPackagingTariffCatQuote_W</a>|
|[Relationship_InventPackagingTariffCatAlloc_WRelationshipId](#Relationship_InventPackagingTariffCatAlloc_WRelationshipId)||<a href="InventPackagingTariffCatQuote_W.md" target="_blank">Group/InventPackagingTariffCatQuote_W</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventPackagingTariffCatQuote_W.md" target="_blank">Group/InventPackagingTariffCatQuote_W</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/InventPackagingTariffCatQuote_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventPackagingTariffCatQuote_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PackagingTariffCatAlloc name="PackagingTariffCatAlloc">PackagingTariffCatAlloc</a>

First included in: Group/InventPackagingTariffCatQuote_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackagingTariffCatAlloc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Percent name="Percent">Percent</a>

First included in: Group/InventPackagingTariffCatQuote_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Percent attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TariffCategoryId name="TariffCategoryId">TariffCategoryId</a>

First included in: Group/InventPackagingTariffCatQuote_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TariffCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/InventPackagingTariffCatQuote_W (this entity)  

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

### <a href=#Relationship_InventPackagingTariffCat_WRelationshipId name="Relationship_InventPackagingTariffCat_WRelationshipId">Relationship_InventPackagingTariffCat_WRelationshipId</a>

First included in: Group/InventPackagingTariffCatQuote_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventPackagingTariffCat_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InventPackagingTariffCat_W.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventPackagingTariffCat_W.cdm.json/InventPackagingTariffCat_W</a></td><td><a href="InventPackagingTariffCat_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventPackagingTariffCatAlloc_WRelationshipId name="Relationship_InventPackagingTariffCatAlloc_WRelationshipId">Relationship_InventPackagingTariffCatAlloc_WRelationshipId</a>

First included in: Group/InventPackagingTariffCatQuote_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventPackagingTariffCatAlloc_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InventPackagingTariffCatAlloc_W.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventPackagingTariffCatAlloc_W.cdm.json/InventPackagingTariffCatAlloc_W</a></td><td><a href="InventPackagingTariffCatAlloc_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/InventPackagingTariffCatQuote_W (this entity)  

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
