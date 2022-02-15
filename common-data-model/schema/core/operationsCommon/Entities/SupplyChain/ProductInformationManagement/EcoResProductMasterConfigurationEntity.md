---
title: EcoResProductMasterConfigurationEntity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Product master configurations in ProductInformationManagement(EcoResProductMasterConfigurationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResProductMasterConfigurationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product master configurations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DimensionTableId](#DimensionTableId)||<a href="EcoResProductMasterConfigurationEntity.md" target="_blank">ProductInformationManagement/EcoResProductMasterConfigurationEntity</a>|
|[ProductMasterNumber](#ProductMasterNumber)||<a href="EcoResProductMasterConfigurationEntity.md" target="_blank">ProductInformationManagement/EcoResProductMasterConfigurationEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="EcoResProductMasterConfigurationEntity.md" target="_blank">ProductInformationManagement/EcoResProductMasterConfigurationEntity</a>|
|[ReplenishmentWeight](#ReplenishmentWeight)||<a href="EcoResProductMasterConfigurationEntity.md" target="_blank">ProductInformationManagement/EcoResProductMasterConfigurationEntity</a>|
|[ContainerUnitSymbol](#ContainerUnitSymbol)||<a href="EcoResProductMasterConfigurationEntity.md" target="_blank">ProductInformationManagement/EcoResProductMasterConfigurationEntity</a>|
|[DisplaySequenceNumber](#DisplaySequenceNumber)||<a href="EcoResProductMasterConfigurationEntity.md" target="_blank">ProductInformationManagement/EcoResProductMasterConfigurationEntity</a>|
|[Relationship_ProductConfigurationRelationshipId](#Relationship_ProductConfigurationRelationshipId)||<a href="EcoResProductMasterConfigurationEntity.md" target="_blank">ProductInformationManagement/EcoResProductMasterConfigurationEntity</a>|
|[Relationship_ProductMasterRelationshipId](#Relationship_ProductMasterRelationshipId)||<a href="EcoResProductMasterConfigurationEntity.md" target="_blank">ProductInformationManagement/EcoResProductMasterConfigurationEntity</a>|
|[BackingTable_EcoResProductMasterConfigurationRelationshipId](#BackingTable_EcoResProductMasterConfigurationRelationshipId)||<a href="EcoResProductMasterConfigurationEntity.md" target="_blank">ProductInformationManagement/EcoResProductMasterConfigurationEntity</a>|

### <a href=#DimensionTableId name="DimensionTableId">DimensionTableId</a>

First included in: ProductInformationManagement/EcoResProductMasterConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductMasterNumber name="ProductMasterNumber">ProductMasterNumber</a>

First included in: ProductInformationManagement/EcoResProductMasterConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductMasterNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProductInformationManagement/EcoResProductMasterConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentWeight name="ReplenishmentWeight">ReplenishmentWeight</a>

First included in: ProductInformationManagement/EcoResProductMasterConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContainerUnitSymbol name="ContainerUnitSymbol">ContainerUnitSymbol</a>

First included in: ProductInformationManagement/EcoResProductMasterConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContainerUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplaySequenceNumber name="DisplaySequenceNumber">DisplaySequenceNumber</a>

First included in: ProductInformationManagement/EcoResProductMasterConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplaySequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProductConfigurationRelationshipId name="Relationship_ProductConfigurationRelationshipId">Relationship_ProductConfigurationRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductMasterConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductConfigurationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductMasterRelationshipId name="Relationship_ProductMasterRelationshipId">Relationship_ProductMasterRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductMasterConfigurationEntity (this entity)  

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

### <a href=#BackingTable_EcoResProductMasterConfigurationRelationshipId name="BackingTable_EcoResProductMasterConfigurationRelationshipId">BackingTable_EcoResProductMasterConfigurationRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductMasterConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResProductMasterConfigurationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResProductMasterConfiguration.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResProductMasterConfiguration.cdm.json/EcoResProductMasterConfiguration</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResProductMasterConfiguration.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
