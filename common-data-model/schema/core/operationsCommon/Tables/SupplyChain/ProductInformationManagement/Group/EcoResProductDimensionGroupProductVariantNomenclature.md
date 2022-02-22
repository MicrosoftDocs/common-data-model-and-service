---
title: EcoResProductDimensionGroupProductVariantNomenclature in Group - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Product variant nomenclature for product dimension group in Group(EcoResProductDimensionGroupProductVariantNomenclature)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Group/EcoResProductDimensionGroupProductVariantNomenclature.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EcoResProductDimensionGroupProductVariantNomenclature/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product variant nomenclature for product dimension group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EcoResProductDimensionGroupProductVariantNomenclature.md" target="_blank">Group/EcoResProductDimensionGroupProductVariantNomenclature</a>|
|[ProductVariantNomenclature](#ProductVariantNomenclature)||<a href="EcoResProductDimensionGroupProductVariantNomenclature.md" target="_blank">Group/EcoResProductDimensionGroupProductVariantNomenclature</a>|
|[NomenclatureRole](#NomenclatureRole)||<a href="EcoResProductDimensionGroupProductVariantNomenclature.md" target="_blank">Group/EcoResProductDimensionGroupProductVariantNomenclature</a>|
|[ProductDimensionGroup](#ProductDimensionGroup)||<a href="EcoResProductDimensionGroupProductVariantNomenclature.md" target="_blank">Group/EcoResProductDimensionGroupProductVariantNomenclature</a>|
|[Relationship_EcoResProductVariantNomenclatureRelationshipId](#Relationship_EcoResProductVariantNomenclatureRelationshipId)||<a href="EcoResProductDimensionGroupProductVariantNomenclature.md" target="_blank">Group/EcoResProductDimensionGroupProductVariantNomenclature</a>|
|[Relationship_EcoResProductDimensionGroupRelationshipId](#Relationship_EcoResProductDimensionGroupRelationshipId)||<a href="EcoResProductDimensionGroupProductVariantNomenclature.md" target="_blank">Group/EcoResProductDimensionGroupProductVariantNomenclature</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/EcoResProductDimensionGroupProductVariantNomenclature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EcoResProductDimensionGroupProductVariantNomenclature/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProductVariantNomenclature name="ProductVariantNomenclature">ProductVariantNomenclature</a>

First included in: Group/EcoResProductDimensionGroupProductVariantNomenclature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVariantNomenclature attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#NomenclatureRole name="NomenclatureRole">NomenclatureRole</a>

First included in: Group/EcoResProductDimensionGroupProductVariantNomenclature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NomenclatureRole attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProductDimensionGroup name="ProductDimensionGroup">ProductDimensionGroup</a>

First included in: Group/EcoResProductDimensionGroupProductVariantNomenclature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDimensionGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_EcoResProductVariantNomenclatureRelationshipId name="Relationship_EcoResProductVariantNomenclatureRelationshipId">Relationship_EcoResProductVariantNomenclatureRelationshipId</a>

First included in: Group/EcoResProductDimensionGroupProductVariantNomenclature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResProductVariantNomenclatureRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/EcoResProductVariantNomenclature.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResProductVariantNomenclature.cdm.json/EcoResProductVariantNomenclature</a></td><td><a href="../Main/EcoResProductVariantNomenclature.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EcoResProductDimensionGroupRelationshipId name="Relationship_EcoResProductDimensionGroupRelationshipId">Relationship_EcoResProductDimensionGroupRelationshipId</a>

First included in: Group/EcoResProductDimensionGroupProductVariantNomenclature (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResProductDimensionGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EcoResProductDimensionGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Group/EcoResProductDimensionGroup.cdm.json/EcoResProductDimensionGroup</a></td><td><a href="EcoResProductDimensionGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
