---
title: EcoResProductSizeGroupLineTranslationEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# EcoResProductSizeGroupLineTranslationEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResProductSizeGroupLineTranslationEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[ProductSizeGroupId](#ProductSizeGroupId)||<a href="EcoResProductSizeGroupLineTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductSizeGroupLineTranslationEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="EcoResProductSizeGroupLineTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductSizeGroupLineTranslationEntity</a>|
|[TranslatedSizeName](#TranslatedSizeName)||<a href="EcoResProductSizeGroupLineTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductSizeGroupLineTranslationEntity</a>|
|[TranslatedSizeDescription](#TranslatedSizeDescription)||<a href="EcoResProductSizeGroupLineTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductSizeGroupLineTranslationEntity</a>|
|[LanguageId](#LanguageId)||<a href="EcoResProductSizeGroupLineTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductSizeGroupLineTranslationEntity</a>|
|[Relationship_ProductSizeGroupLineRelationshipId](#Relationship_ProductSizeGroupLineRelationshipId)||<a href="EcoResProductSizeGroupLineTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductSizeGroupLineTranslationEntity</a>|
|[BackingTable_RetailSizeGroupTransTranslationRelationshipId](#BackingTable_RetailSizeGroupTransTranslationRelationshipId)||<a href="EcoResProductSizeGroupLineTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductSizeGroupLineTranslationEntity</a>|

### <a href=#ProductSizeGroupId name="ProductSizeGroupId">ProductSizeGroupId</a>

First included in: ProductInformationManagement/EcoResProductSizeGroupLineTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: ProductInformationManagement/EcoResProductSizeGroupLineTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslatedSizeName name="TranslatedSizeName">TranslatedSizeName</a>

First included in: ProductInformationManagement/EcoResProductSizeGroupLineTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslatedSizeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslatedSizeDescription name="TranslatedSizeDescription">TranslatedSizeDescription</a>

First included in: ProductInformationManagement/EcoResProductSizeGroupLineTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslatedSizeDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: ProductInformationManagement/EcoResProductSizeGroupLineTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProductSizeGroupLineRelationshipId name="Relationship_ProductSizeGroupLineRelationshipId">Relationship_ProductSizeGroupLineRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductSizeGroupLineTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductSizeGroupLineRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_RetailSizeGroupTransTranslationRelationshipId name="BackingTable_RetailSizeGroupTransTranslationRelationshipId">BackingTable_RetailSizeGroupTransTranslationRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductSizeGroupLineTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailSizeGroupTransTranslationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/Retail/Miscellaneous/RetailSizeGroupTransTranslation.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailSizeGroupTransTranslation.cdm.json/RetailSizeGroupTransTranslation</a></td><td><a href="../../../Tables/Commerce/Retail/Miscellaneous/RetailSizeGroupTransTranslation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
