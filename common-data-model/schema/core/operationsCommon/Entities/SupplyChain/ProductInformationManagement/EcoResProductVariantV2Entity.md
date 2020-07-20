---
title: EcoResProductVariantV2Entity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Product variants V2 in ProductInformationManagement(EcoResProductVariantV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResProductVariantV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product variants V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProductMasterNumber](#ProductMasterNumber)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[ProductVariantNumber](#ProductVariantNumber)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[ProductName](#ProductName)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[ProductSearchName](#ProductSearchName)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[ProductDescription](#ProductDescription)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[ProductColorId](#ProductColorId)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[InternalConfigurationId](#InternalConfigurationId)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[InternalSizeId](#InternalSizeId)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[InternalColorId](#InternalColorId)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[InternalStyleId](#InternalStyleId)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[InternalVersionId](#InternalVersionId)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[ConfigurationProductDimensionAttributeRecId](#ConfigurationProductDimensionAttributeRecId)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[SizeProductDimensionAttributeRecId](#SizeProductDimensionAttributeRecId)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[ColorProductDimensionAttributeRecId](#ColorProductDimensionAttributeRecId)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[StyleProductDimensionAttributeRecId](#StyleProductDimensionAttributeRecId)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[VersionProductDimensionAttributeRecId](#VersionProductDimensionAttributeRecId)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[Relationship_ProductMasterRelationshipId](#Relationship_ProductMasterRelationshipId)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|
|[BackingTable_EcoResDistinctProductVariantRelationshipId](#BackingTable_EcoResDistinctProductVariantRelationshipId)||<a href="EcoResProductVariantV2Entity.md" target="_blank">ProductInformationManagement/EcoResProductVariantV2Entity</a>|

### <a href=#ProductMasterNumber name="ProductMasterNumber">ProductMasterNumber</a>

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product master number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductMasterNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product master number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVariantNumber name="ProductVariantNumber">ProductVariantNumber</a>

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product variant number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVariantNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product variant number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductName name="ProductName">ProductName</a>

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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

First included in: ProductInformationManagement/EcoResProductVariantV2Entity (this entity)  

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
