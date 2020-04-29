---
title: AssetImpairmentCashGeneratingUnitAssetEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# CGU related assets

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CGU related assets</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ImpairmentCGU](#ImpairmentCGU)||<a href="AssetImpairmentCashGeneratingUnitAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity</a>|
|[CashGeneratingUnitNumber](#CashGeneratingUnitNumber)||<a href="AssetImpairmentCashGeneratingUnitAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity</a>|
|[AssetNumber](#AssetNumber)||<a href="AssetImpairmentCashGeneratingUnitAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity</a>|
|[Book](#Book)||<a href="AssetImpairmentCashGeneratingUnitAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity</a>|
|[AllocationPriority](#AllocationPriority)||<a href="AssetImpairmentCashGeneratingUnitAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity</a>|
|[ImpairmentAllocationMethod](#ImpairmentAllocationMethod)||<a href="AssetImpairmentCashGeneratingUnitAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity</a>|
|[ImpairmentHoldingAssetId](#ImpairmentHoldingAssetId)||<a href="AssetImpairmentCashGeneratingUnitAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity</a>|
|[ImpairmentHoldingBookId](#ImpairmentHoldingBookId)||<a href="AssetImpairmentCashGeneratingUnitAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity</a>|
|[BackingTable_AssetImpairmentCGUAssets_JPRelationshipId](#BackingTable_AssetImpairmentCGUAssets_JPRelationshipId)||<a href="AssetImpairmentCashGeneratingUnitAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="AssetImpairmentCashGeneratingUnitAssetEntity.md" target="_blank">FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity</a>|

### <a href=#ImpairmentCGU name="ImpairmentCGU">ImpairmentCGU</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImpairmentCGU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashGeneratingUnitNumber name="CashGeneratingUnitNumber">CashGeneratingUnitNumber</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashGeneratingUnitNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetNumber name="AssetNumber">AssetNumber</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity (this entity)  

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

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity (this entity)  

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

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity (this entity)  

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

### <a href=#ImpairmentAllocationMethod name="ImpairmentAllocationMethod">ImpairmentAllocationMethod</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImpairmentAllocationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ImpairmentHoldingAssetId name="ImpairmentHoldingAssetId">ImpairmentHoldingAssetId</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImpairmentHoldingAssetId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ImpairmentHoldingBookId name="ImpairmentHoldingBookId">ImpairmentHoldingBookId</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ImpairmentHoldingBookId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_AssetImpairmentCGUAssets_JPRelationshipId name="BackingTable_AssetImpairmentCGUAssets_JPRelationshipId">BackingTable_AssetImpairmentCGUAssets_JPRelationshipId</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_AssetImpairmentCGUAssets_JPRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FixedAssets/Miscellaneous/AssetImpairmentCGUAssets_JP.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Miscellaneous/AssetImpairmentCGUAssets_JP.cdm.json/AssetImpairmentCGUAssets_JP</a></td><td><a href="../../../Tables/Finance/FixedAssets/Miscellaneous/AssetImpairmentCGUAssets_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: FixedAssets/AssetImpairmentCashGeneratingUnitAssetEntity (this entity)  

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
