---
title: AssetImpairmentCashGeneratingUnitSharedAssetEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Shared assets and goodwill

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shared assets and goodwill</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CGUGroup](#CGUGroup)||<a href="AssetImpairmentCashGeneratingUnitSharedAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity</a>|
|[CGUGroupName](#CGUGroupName)||<a href="AssetImpairmentCashGeneratingUnitSharedAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity</a>|
|[AssetNumber](#AssetNumber)||<a href="AssetImpairmentCashGeneratingUnitSharedAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity</a>|
|[Book](#Book)||<a href="AssetImpairmentCashGeneratingUnitSharedAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity</a>|
|[AllocationPriority](#AllocationPriority)||<a href="AssetImpairmentCashGeneratingUnitSharedAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity</a>|
|[NetSellingPrice](#NetSellingPrice)||<a href="AssetImpairmentCashGeneratingUnitSharedAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity</a>|
|[ProrationMethodOverride](#ProrationMethodOverride)||<a href="AssetImpairmentCashGeneratingUnitSharedAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity</a>|
|[SharedAssetType](#SharedAssetType)||<a href="AssetImpairmentCashGeneratingUnitSharedAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity</a>|
|[BackingTable_AssetImpairmentCGUSharedAssets_JPRelationshipId](#BackingTable_AssetImpairmentCGUSharedAssets_JPRelationshipId)||<a href="AssetImpairmentCashGeneratingUnitSharedAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="AssetImpairmentCashGeneratingUnitSharedAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity</a>|

### <a href=#CGUGroup name="CGUGroup">CGUGroup</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CGUGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CGUGroupName name="CGUGroupName">CGUGroupName</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CGUGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetNumber name="AssetNumber">AssetNumber</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Book name="Book">Book</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Book attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllocationPriority name="AllocationPriority">AllocationPriority</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllocationPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetSellingPrice name="NetSellingPrice">NetSellingPrice</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetSellingPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProrationMethodOverride name="ProrationMethodOverride">ProrationMethodOverride</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProrationMethodOverride attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SharedAssetType name="SharedAssetType">SharedAssetType</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SharedAssetType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_AssetImpairmentCGUSharedAssets_JPRelationshipId name="BackingTable_AssetImpairmentCGUSharedAssets_JPRelationshipId">BackingTable_AssetImpairmentCGUSharedAssets_JPRelationshipId</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_AssetImpairmentCGUSharedAssets_JPRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FixedAssets/Miscellaneous/AssetImpairmentCGUSharedAssets_JP.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Miscellaneous/AssetImpairmentCGUSharedAssets_JP.cdm.json/AssetImpairmentCGUSharedAssets_JP</a></td><td><a href="../../../Tables/Finance/FixedAssets/Miscellaneous/AssetImpairmentCGUSharedAssets_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitSharedAssetEntity (this entity)  

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
