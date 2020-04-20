---
title: DimensionAttributeTranslationEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# DimensionAttributeTranslationEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/FinancialDimensions/DimensionAttributeTranslationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DimensionAttribute](#DimensionAttribute)||<a href="DimensionAttributeTranslationEntity.md" target="_blank">FinancialDimensions/DimensionAttributeTranslationEntity</a>|
|[FinancialDimension](#FinancialDimension)||<a href="DimensionAttributeTranslationEntity.md" target="_blank">FinancialDimensions/DimensionAttributeTranslationEntity</a>|
|[LanguageCode](#LanguageCode)||<a href="DimensionAttributeTranslationEntity.md" target="_blank">FinancialDimensions/DimensionAttributeTranslationEntity</a>|
|[TranslatedFinancialDimension](#TranslatedFinancialDimension)||<a href="DimensionAttributeTranslationEntity.md" target="_blank">FinancialDimensions/DimensionAttributeTranslationEntity</a>|
|[Relationship_DimensionAttributeEntityRelationshipId](#Relationship_DimensionAttributeEntityRelationshipId)||<a href="DimensionAttributeTranslationEntity.md" target="_blank">FinancialDimensions/DimensionAttributeTranslationEntity</a>|
|[BackingTable_DimensionAttributeTranslationRelationshipId](#BackingTable_DimensionAttributeTranslationRelationshipId)||<a href="DimensionAttributeTranslationEntity.md" target="_blank">FinancialDimensions/DimensionAttributeTranslationEntity</a>|

### <a href=#DimensionAttribute name="DimensionAttribute">DimensionAttribute</a>

First included in: FinancialDimensions/DimensionAttributeTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionAttribute attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FinancialDimension name="FinancialDimension">FinancialDimension</a>

First included in: FinancialDimensions/DimensionAttributeTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageCode name="LanguageCode">LanguageCode</a>

First included in: FinancialDimensions/DimensionAttributeTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslatedFinancialDimension name="TranslatedFinancialDimension">TranslatedFinancialDimension</a>

First included in: FinancialDimensions/DimensionAttributeTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslatedFinancialDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionAttributeEntityRelationshipId name="Relationship_DimensionAttributeEntityRelationshipId">Relationship_DimensionAttributeEntityRelationshipId</a>

First included in: FinancialDimensions/DimensionAttributeTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_DimensionAttributeTranslationRelationshipId name="BackingTable_DimensionAttributeTranslationRelationshipId">BackingTable_DimensionAttributeTranslationRelationshipId</a>

First included in: FinancialDimensions/DimensionAttributeTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_DimensionAttributeTranslationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FinancialDimensions/Main/DimensionAttributeTranslation.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeTranslation.cdm.json/DimensionAttributeTranslation</a></td><td><a href="../../../Tables/Finance/FinancialDimensions/Main/DimensionAttributeTranslation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
