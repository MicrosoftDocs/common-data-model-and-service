---
title: AssetGroupValueModelSetupEntity in FixedAssets - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Fixed asset group book setup in FixedAssets(AssetGroupValueModelSetupEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/FixedAssets/AssetGroupValueModelSetupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed asset group book setup</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FixedAssetGroupId](#FixedAssetGroupId)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[ValueModelId](#ValueModelId)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[CalculateDepreciation](#CalculateDepreciation)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[DepreciationConvention](#DepreciationConvention)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[DepreciationPeriods](#DepreciationPeriods)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[DepreciationProfileId](#DepreciationProfileId)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[AlternativeDepreciationProfileId](#AlternativeDepreciationProfileId)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[ExtraordinaryDepreciationProfileId](#ExtraordinaryDepreciationProfileId)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[ServiceLife](#ServiceLife)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[AllowableLimitForAccumulatedDepreciation](#AllowableLimitForAccumulatedDepreciation)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[ServiceLifeMonths](#ServiceLifeMonths)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[ServiceLifeYears](#ServiceLifeYears)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[SpecialDepreciationAllocationPeriods](#SpecialDepreciationAllocationPeriods)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[SpecialDepreciationAllocationUnit](#SpecialDepreciationAllocationUnit)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[SpecialDepreciationAllocationStartConvention](#SpecialDepreciationAllocationStartConvention)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[AcceleratedDepreciationProfileId](#AcceleratedDepreciationProfileId)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[IsAssetGroupDepreciation](#IsAssetGroupDepreciation)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[DepreciationGroupId](#DepreciationGroupId)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[Relationship_AssetGroupEntityRelationshipId](#Relationship_AssetGroupEntityRelationshipId)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[Relationship_AssetBookTableRelationshipId](#Relationship_AssetBookTableRelationshipId)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[Relationship_AssetDepreciationProfileRelationshipId](#Relationship_AssetDepreciationProfileRelationshipId)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[Relationship_AssetAlternativeDepreciationProfileRelationshipId](#Relationship_AssetAlternativeDepreciationProfileRelationshipId)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[Relationship_AssetExtraordinaryDepreciationProfileRelationshipId](#Relationship_AssetExtraordinaryDepreciationProfileRelationshipId)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[Relationship_AssetAcceleratedDepreciationProfileRelationshipId](#Relationship_AssetAcceleratedDepreciationProfileRelationshipId)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[BackingTable_AssetGroupBookSetupRelationshipId](#BackingTable_AssetGroupBookSetupRelationshipId)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="AssetGroupValueModelSetupEntity.md" target="_blank">FixedAssets/AssetGroupValueModelSetupEntity</a>|

### <a href=#FixedAssetGroupId name="FixedAssetGroupId">FixedAssetGroupId</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValueModelId name="ValueModelId">ValueModelId</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValueModelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculateDepreciation name="CalculateDepreciation">CalculateDepreciation</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculateDepreciation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationConvention name="DepreciationConvention">DepreciationConvention</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationConvention attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationPeriods name="DepreciationPeriods">DepreciationPeriods</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationPeriods attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationProfileId name="DepreciationProfileId">DepreciationProfileId</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternativeDepreciationProfileId name="AlternativeDepreciationProfileId">AlternativeDepreciationProfileId</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternativeDepreciationProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExtraordinaryDepreciationProfileId name="ExtraordinaryDepreciationProfileId">ExtraordinaryDepreciationProfileId</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtraordinaryDepreciationProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceLife name="ServiceLife">ServiceLife</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceLife attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowableLimitForAccumulatedDepreciation name="AllowableLimitForAccumulatedDepreciation">AllowableLimitForAccumulatedDepreciation</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowableLimitForAccumulatedDepreciation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceLifeMonths name="ServiceLifeMonths">ServiceLifeMonths</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceLifeMonths attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServiceLifeYears name="ServiceLifeYears">ServiceLifeYears</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceLifeYears attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialDepreciationAllocationPeriods name="SpecialDepreciationAllocationPeriods">SpecialDepreciationAllocationPeriods</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepreciationAllocationPeriods attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialDepreciationAllocationUnit name="SpecialDepreciationAllocationUnit">SpecialDepreciationAllocationUnit</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepreciationAllocationUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialDepreciationAllocationStartConvention name="SpecialDepreciationAllocationStartConvention">SpecialDepreciationAllocationStartConvention</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepreciationAllocationStartConvention attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcceleratedDepreciationProfileId name="AcceleratedDepreciationProfileId">AcceleratedDepreciationProfileId</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceleratedDepreciationProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAssetGroupDepreciation name="IsAssetGroupDepreciation">IsAssetGroupDepreciation</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAssetGroupDepreciation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationGroupId name="DepreciationGroupId">DepreciationGroupId</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetGroupEntityRelationshipId name="Relationship_AssetGroupEntityRelationshipId">Relationship_AssetGroupEntityRelationshipId</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetGroupEntityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetBookTableRelationshipId name="Relationship_AssetBookTableRelationshipId">Relationship_AssetBookTableRelationshipId</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetDepreciationProfileRelationshipId name="Relationship_AssetDepreciationProfileRelationshipId">Relationship_AssetDepreciationProfileRelationshipId</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetDepreciationProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetAlternativeDepreciationProfileRelationshipId name="Relationship_AssetAlternativeDepreciationProfileRelationshipId">Relationship_AssetAlternativeDepreciationProfileRelationshipId</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetAlternativeDepreciationProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetExtraordinaryDepreciationProfileRelationshipId name="Relationship_AssetExtraordinaryDepreciationProfileRelationshipId">Relationship_AssetExtraordinaryDepreciationProfileRelationshipId</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetExtraordinaryDepreciationProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetAcceleratedDepreciationProfileRelationshipId name="Relationship_AssetAcceleratedDepreciationProfileRelationshipId">Relationship_AssetAcceleratedDepreciationProfileRelationshipId</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetAcceleratedDepreciationProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_AssetGroupBookSetupRelationshipId name="BackingTable_AssetGroupBookSetupRelationshipId">BackingTable_AssetGroupBookSetupRelationshipId</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_AssetGroupBookSetupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FixedAssets/Group/AssetGroupBookSetup.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Group/AssetGroupBookSetup.cdm.json/AssetGroupBookSetup</a></td><td><a href="../../../Tables/Finance/FixedAssets/Group/AssetGroupBookSetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: FixedAssets/AssetGroupValueModelSetupEntity (this entity)  

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
