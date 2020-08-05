---
title: EcoResProductAttributeEnumerationValueTypeTranslationEntity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Product attribute enumeration type translations in ProductInformationManagement(EcoResProductAttributeEnumerationValueTypeTranslationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResProductAttributeEnumerationValueTypeTranslationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product attribute enumeration type translations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProductAttributeEnumerationName](#ProductAttributeEnumerationName)||<a href="EcoResProductAttributeEnumerationValueTypeTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductAttributeEnumerationValueTypeTranslationEntity</a>|
|[ProductAttributeEnumerationValue](#ProductAttributeEnumerationValue)||<a href="EcoResProductAttributeEnumerationValueTypeTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductAttributeEnumerationValueTypeTranslationEntity</a>|
|[LanguageId](#LanguageId)||<a href="EcoResProductAttributeEnumerationValueTypeTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductAttributeEnumerationValueTypeTranslationEntity</a>|
|[TranslatedEnumerationValue](#TranslatedEnumerationValue)||<a href="EcoResProductAttributeEnumerationValueTypeTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductAttributeEnumerationValueTypeTranslationEntity</a>|
|[BackingTable_EcoResTextValueTranslationRelationshipId](#BackingTable_EcoResTextValueTranslationRelationshipId)||<a href="EcoResProductAttributeEnumerationValueTypeTranslationEntity.md" target="_blank">ProductInformationManagement/EcoResProductAttributeEnumerationValueTypeTranslationEntity</a>|

### <a href=#ProductAttributeEnumerationName name="ProductAttributeEnumerationName">ProductAttributeEnumerationName</a>

First included in: ProductInformationManagement/EcoResProductAttributeEnumerationValueTypeTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductAttributeEnumerationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductAttributeEnumerationValue name="ProductAttributeEnumerationValue">ProductAttributeEnumerationValue</a>

First included in: ProductInformationManagement/EcoResProductAttributeEnumerationValueTypeTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductAttributeEnumerationValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: ProductInformationManagement/EcoResProductAttributeEnumerationValueTypeTranslationEntity (this entity)  

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

### <a href=#TranslatedEnumerationValue name="TranslatedEnumerationValue">TranslatedEnumerationValue</a>

First included in: ProductInformationManagement/EcoResProductAttributeEnumerationValueTypeTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TranslatedEnumerationValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_EcoResTextValueTranslationRelationshipId name="BackingTable_EcoResTextValueTranslationRelationshipId">BackingTable_EcoResTextValueTranslationRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductAttributeEnumerationValueTypeTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResTextValueTranslationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResTextValueTranslation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResTextValueTranslation.cdm.json/EcoResTextValueTranslation</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResTextValueTranslation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
