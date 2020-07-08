---
title: EcoResProductCategoryTranslationEntity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Product category translations in ProductInformationManagement(EcoResProductCategoryTranslationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResProductCategoryTranslationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product category translations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProductCategoryHierarchyId](#ProductCategoryHierarchyId)||<a href="EcoResProductCategoryTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductCategoryTranslationEntity</a>|
|[ProductCategoryId](#ProductCategoryId)||<a href="EcoResProductCategoryTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductCategoryTranslationEntity</a>|
|[ProductCategoryHierarchyName](#ProductCategoryHierarchyName)||<a href="EcoResProductCategoryTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductCategoryTranslationEntity</a>|
|[ProductCategoryName](#ProductCategoryName)||<a href="EcoResProductCategoryTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductCategoryTranslationEntity</a>|
|[LanguageId](#LanguageId)||<a href="EcoResProductCategoryTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductCategoryTranslationEntity</a>|
|[TranslatedCategoryDescription](#TranslatedCategoryDescription)||<a href="EcoResProductCategoryTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductCategoryTranslationEntity</a>|
|[TranslatedFriendlyCategoryName](#TranslatedFriendlyCategoryName)||<a href="EcoResProductCategoryTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductCategoryTranslationEntity</a>|
|[TranslatedCategoryKeywords](#TranslatedCategoryKeywords)||<a href="EcoResProductCategoryTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductCategoryTranslationEntity</a>|
|[BackingTable_EcoResCategoryTranslationRelationshipId](#BackingTable_EcoResCategoryTranslationRelationshipId)||<a href="EcoResProductCategoryTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductCategoryTranslationEntity</a>|

### <a href=#ProductCategoryHierarchyId name="ProductCategoryHierarchyId">ProductCategoryHierarchyId</a>

First included in: ProductInformationManagement/EcoResProductCategoryTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCategoryHierarchyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCategoryId name="ProductCategoryId">ProductCategoryId</a>

First included in: ProductInformationManagement/EcoResProductCategoryTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCategoryHierarchyName name="ProductCategoryHierarchyName">ProductCategoryHierarchyName</a>

First included in: ProductInformationManagement/EcoResProductCategoryTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCategoryHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCategoryName name="ProductCategoryName">ProductCategoryName</a>

First included in: ProductInformationManagement/EcoResProductCategoryTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: ProductInformationManagement/EcoResProductCategoryTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslatedCategoryDescription name="TranslatedCategoryDescription">TranslatedCategoryDescription</a>

First included in: ProductInformationManagement/EcoResProductCategoryTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslatedCategoryDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslatedFriendlyCategoryName name="TranslatedFriendlyCategoryName">TranslatedFriendlyCategoryName</a>

First included in: ProductInformationManagement/EcoResProductCategoryTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslatedFriendlyCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TranslatedCategoryKeywords name="TranslatedCategoryKeywords">TranslatedCategoryKeywords</a>

First included in: ProductInformationManagement/EcoResProductCategoryTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslatedCategoryKeywords attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_EcoResCategoryTranslationRelationshipId name="BackingTable_EcoResCategoryTranslationRelationshipId">BackingTable_EcoResCategoryTranslationRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductCategoryTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResCategoryTranslationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategoryTranslation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategoryTranslation.cdm.json/EcoResCategoryTranslation</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategoryTranslation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
