---
title: EcoResProductVariantConfiguration in Main - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Product variants configurations in Main(EcoResProductVariantConfiguration)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResProductVariantConfiguration.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EcoResProductVariantConfiguration/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product variant - dimension values</td></tr><tr><td>en</td><td>Product variants configurations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EcoResProductVariantConfiguration.md" target="_blank">Main/EcoResProductVariantConfiguration</a>|
|[DistinctProductVariant](#DistinctProductVariant)||<a href="EcoResProductVariantConfiguration.md" target="_blank">Main/EcoResProductVariantConfiguration</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="EcoResProductVariantConfiguration.md" target="_blank">Main/EcoResProductVariantConfiguration</a>|
|[ProductDimensionAttribute](#ProductDimensionAttribute)||<a href="EcoResProductVariantConfiguration.md" target="_blank">Main/EcoResProductVariantConfiguration</a>|
|[RetailWeight](#RetailWeight)||<a href="EcoResProductVariantConfiguration.md" target="_blank">Main/EcoResProductVariantConfiguration</a>|
|[RetailDisplayOrder](#RetailDisplayOrder)||<a href="EcoResProductVariantConfiguration.md" target="_blank">Main/EcoResProductVariantConfiguration</a>|
|[Relationship_EcoResDistinctProductVariantRelationshipId](#Relationship_EcoResDistinctProductVariantRelationshipId)||<a href="EcoResProductVariantConfiguration.md" target="_blank">Main/EcoResProductVariantConfiguration</a>|
|[Relationship_EcoResProductDimensionAttributeRelationshipId](#Relationship_EcoResProductDimensionAttributeRelationshipId)||<a href="EcoResProductVariantConfiguration.md" target="_blank">Main/EcoResProductVariantConfiguration</a>|
|[Configuration](#Configuration)||<a href="EcoResProductVariantConfiguration.md" target="_blank">Main/EcoResProductVariantConfiguration</a>|
|[Relationship_EcoResConfigurationRelationshipId](#Relationship_EcoResConfigurationRelationshipId)||<a href="EcoResProductVariantConfiguration.md" target="_blank">Main/EcoResProductVariantConfiguration</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/EcoResProductVariantConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EcoResProductVariantConfiguration/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DistinctProductVariant name="DistinctProductVariant">DistinctProductVariant</a>

First included in: Main/EcoResProductVariantConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product variants</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DistinctProductVariant attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product variants</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Main/EcoResProductVariantConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProductDimensionAttribute name="ProductDimensionAttribute">ProductDimensionAttribute</a>

First included in: Main/EcoResProductVariantConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product dimension attributes</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDimensionAttribute attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product dimension attributes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailWeight name="RetailWeight">RetailWeight</a>

First included in: Main/EcoResProductVariantConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailWeight attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RetailDisplayOrder name="RetailDisplayOrder">RetailDisplayOrder</a>

First included in: Main/EcoResProductVariantConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailDisplayOrder attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Relationship_EcoResDistinctProductVariantRelationshipId name="Relationship_EcoResDistinctProductVariantRelationshipId">Relationship_EcoResDistinctProductVariantRelationshipId</a>

First included in: Main/EcoResProductVariantConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResDistinctProductVariantRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EcoResDistinctProductVariant.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResDistinctProductVariant.cdm.json/EcoResDistinctProductVariant</a></td><td><a href="EcoResDistinctProductVariant.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EcoResProductDimensionAttributeRelationshipId name="Relationship_EcoResProductDimensionAttributeRelationshipId">Relationship_EcoResProductDimensionAttributeRelationshipId</a>

First included in: Main/EcoResProductVariantConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResProductDimensionAttributeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/EcoResProductDimensionAttribute.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Group/EcoResProductDimensionAttribute.cdm.json/EcoResProductDimensionAttribute</a></td><td><a href="../Group/EcoResProductDimensionAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Configuration name="Configuration">Configuration</a>

First included in: Main/EcoResProductVariantConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Configuration attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_EcoResConfigurationRelationshipId name="Relationship_EcoResConfigurationRelationshipId">Relationship_EcoResConfigurationRelationshipId</a>

First included in: Main/EcoResProductVariantConfiguration (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResConfigurationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EcoResConfiguration.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResConfiguration.cdm.json/EcoResConfiguration</a></td><td><a href="EcoResConfiguration.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
