---
title: AssetImpairmentCashGeneratingUnitGroupEntity in FixedAssets - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# CGU group in FixedAssets(AssetImpairmentCashGeneratingUnitGroupEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CGU group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CGUGroup](#CGUGroup)||<a href="AssetImpairmentCashGeneratingUnitGroupEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity</a>|
|[Description](#Description)||<a href="AssetImpairmentCashGeneratingUnitGroupEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity</a>|
|[Status](#Status)||<a href="AssetImpairmentCashGeneratingUnitGroupEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity</a>|
|[PostingLayer](#PostingLayer)||<a href="AssetImpairmentCashGeneratingUnitGroupEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity</a>|
|[ProrationMethod](#ProrationMethod)||<a href="AssetImpairmentCashGeneratingUnitGroupEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity</a>|
|[ImpairmentMethod](#ImpairmentMethod)||<a href="AssetImpairmentCashGeneratingUnitGroupEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity</a>|
|[SharedAssetHasHigherPriority](#SharedAssetHasHigherPriority)||<a href="AssetImpairmentCashGeneratingUnitGroupEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity</a>|
|[BackingTable_AssetImpairmentCGUGroup_JPRelationshipId](#BackingTable_AssetImpairmentCGUGroup_JPRelationshipId)||<a href="AssetImpairmentCashGeneratingUnitGroupEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="AssetImpairmentCashGeneratingUnitGroupEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity</a>|

### <a href=#CGUGroup name="CGUGroup">CGUGroup</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CGUGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingLayer name="PostingLayer">PostingLayer</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingLayer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProrationMethod name="ProrationMethod">ProrationMethod</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProrationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ImpairmentMethod name="ImpairmentMethod">ImpairmentMethod</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImpairmentMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SharedAssetHasHigherPriority name="SharedAssetHasHigherPriority">SharedAssetHasHigherPriority</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shared asset priority</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SharedAssetHasHigherPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shared asset priority</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_AssetImpairmentCGUGroup_JPRelationshipId name="BackingTable_AssetImpairmentCGUGroup_JPRelationshipId">BackingTable_AssetImpairmentCGUGroup_JPRelationshipId</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_AssetImpairmentCGUGroup_JPRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FixedAssets/Group/AssetImpairmentCGUGroup_JP.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Group/AssetImpairmentCGUGroup_JP.cdm.json/AssetImpairmentCGUGroup_JP</a></td><td><a href="../../../Tables/Finance/FixedAssets/Group/AssetImpairmentCGUGroup_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
