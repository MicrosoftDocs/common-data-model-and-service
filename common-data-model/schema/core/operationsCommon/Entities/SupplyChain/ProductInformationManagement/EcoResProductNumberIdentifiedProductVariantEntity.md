---
title: EcoResProductNumberIdentifiedProductVariantEntity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Product variants by product number identification in ProductInformationManagement(EcoResProductNumberIdentifiedProductVariantEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product variants by product number identification</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProductMasterNumber](#ProductMasterNumber)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[ProductVariantNumber](#ProductVariantNumber)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[ProductName](#ProductName)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[ProductSearchName](#ProductSearchName)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[ProductDescription](#ProductDescription)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[InternalConfigurationId](#InternalConfigurationId)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[InternalSizeId](#InternalSizeId)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[InternalColorId](#InternalColorId)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[InternalStyleId](#InternalStyleId)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[InternalVersionId](#InternalVersionId)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[ConfigurationProductDimensionAttributeRecId](#ConfigurationProductDimensionAttributeRecId)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[SizeProductDimensionAttributeRecId](#SizeProductDimensionAttributeRecId)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[ColorProductDimensionAttributeRecId](#ColorProductDimensionAttributeRecId)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[StyleProductDimensionAttributeRecId](#StyleProductDimensionAttributeRecId)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[VersionProductDimensionAttributeRecId](#VersionProductDimensionAttributeRecId)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[Relationship_ProductMasterRelationshipId](#Relationship_ProductMasterRelationshipId)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|
|[BackingTable_EcoResDistinctProductVariantRelationshipId](#BackingTable_EcoResDistinctProductVariantRelationshipId)||<a href="EcoResProductNumberIdentifiedProductVariantEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity</a>|

### <a href=#ProductMasterNumber name="ProductMasterNumber">ProductMasterNumber</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product master number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductMasterNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product master number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVariantNumber name="ProductVariantNumber">ProductVariantNumber</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product variant number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVariantNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product variant number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductName name="ProductName">ProductName</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSearchName name="ProductSearchName">ProductSearchName</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSearchName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductDescription name="ProductDescription">ProductDescription</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InternalConfigurationId name="InternalConfigurationId">InternalConfigurationId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InternalSizeId name="InternalSizeId">InternalSizeId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InternalColorId name="InternalColorId">InternalColorId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InternalStyleId name="InternalStyleId">InternalStyleId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InternalVersionId name="InternalVersionId">InternalVersionId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfigurationProductDimensionAttributeRecId name="ConfigurationProductDimensionAttributeRecId">ConfigurationProductDimensionAttributeRecId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfigurationProductDimensionAttributeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SizeProductDimensionAttributeRecId name="SizeProductDimensionAttributeRecId">SizeProductDimensionAttributeRecId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SizeProductDimensionAttributeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColorProductDimensionAttributeRecId name="ColorProductDimensionAttributeRecId">ColorProductDimensionAttributeRecId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColorProductDimensionAttributeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StyleProductDimensionAttributeRecId name="StyleProductDimensionAttributeRecId">StyleProductDimensionAttributeRecId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StyleProductDimensionAttributeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionProductDimensionAttributeRecId name="VersionProductDimensionAttributeRecId">VersionProductDimensionAttributeRecId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionProductDimensionAttributeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProductMasterRelationshipId name="Relationship_ProductMasterRelationshipId">Relationship_ProductMasterRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductMasterRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_EcoResDistinctProductVariantRelationshipId name="BackingTable_EcoResDistinctProductVariantRelationshipId">BackingTable_EcoResDistinctProductVariantRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedProductVariantEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResDistinctProductVariantRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResDistinctProductVariant.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResDistinctProductVariant.cdm.json/EcoResDistinctProductVariant</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResDistinctProductVariant.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
