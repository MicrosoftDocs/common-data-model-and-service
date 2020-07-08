---
title: EcoResPhysicalProductDimensionDetailsEntity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Physical product dimension details in ProductInformationManagement(EcoResPhysicalProductDimensionDetailsEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Physical product dimension details</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Product](#Product)||<a href="EcoResPhysicalProductDimensionDetailsEntity.md" target="_blank">ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity</a>|
|[DimensionType](#DimensionType)||<a href="EcoResPhysicalProductDimensionDetailsEntity.md" target="_blank">ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity</a>|
|[PhysicalUnitSymbol](#PhysicalUnitSymbol)||<a href="EcoResPhysicalProductDimensionDetailsEntity.md" target="_blank">ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity</a>|
|[PhysicalDepth](#PhysicalDepth)||<a href="EcoResPhysicalProductDimensionDetailsEntity.md" target="_blank">ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity</a>|
|[PhysicalHeight](#PhysicalHeight)||<a href="EcoResPhysicalProductDimensionDetailsEntity.md" target="_blank">ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity</a>|
|[PhysicalWeight](#PhysicalWeight)||<a href="EcoResPhysicalProductDimensionDetailsEntity.md" target="_blank">ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity</a>|
|[PhysicalWidth](#PhysicalWidth)||<a href="EcoResPhysicalProductDimensionDetailsEntity.md" target="_blank">ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity</a>|
|[MassUnitSymbol](#MassUnitSymbol)||<a href="EcoResPhysicalProductDimensionDetailsEntity.md" target="_blank">ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity</a>|
|[LengthUnitSymbol](#LengthUnitSymbol)||<a href="EcoResPhysicalProductDimensionDetailsEntity.md" target="_blank">ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity</a>|
|[VolumeUnitSymbol](#VolumeUnitSymbol)||<a href="EcoResPhysicalProductDimensionDetailsEntity.md" target="_blank">ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity</a>|
|[ProductNumber](#ProductNumber)||<a href="EcoResPhysicalProductDimensionDetailsEntity.md" target="_blank">ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity</a>|
|[Relationship_ProductV2RelationshipId](#Relationship_ProductV2RelationshipId)||<a href="EcoResPhysicalProductDimensionDetailsEntity.md" target="_blank">ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity</a>|
|[Relationship_MassUnitOfMeasureRelationshipId](#Relationship_MassUnitOfMeasureRelationshipId)||<a href="EcoResPhysicalProductDimensionDetailsEntity.md" target="_blank">ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity</a>|
|[Relationship_LengthUnitOfMeasureRelationshipId](#Relationship_LengthUnitOfMeasureRelationshipId)||<a href="EcoResPhysicalProductDimensionDetailsEntity.md" target="_blank">ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity</a>|
|[Relationship_VolumeUnitOfMeasureRelationshipId](#Relationship_VolumeUnitOfMeasureRelationshipId)||<a href="EcoResPhysicalProductDimensionDetailsEntity.md" target="_blank">ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity</a>|
|[Relationship_PhysicalUnitOfMeasureRelationshipId](#Relationship_PhysicalUnitOfMeasureRelationshipId)||<a href="EcoResPhysicalProductDimensionDetailsEntity.md" target="_blank">ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity</a>|
|[BackingTable_EcoResPhysicalProductDimensionsRelationshipId](#BackingTable_EcoResPhysicalProductDimensionsRelationshipId)||<a href="EcoResPhysicalProductDimensionDetailsEntity.md" target="_blank">ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity</a>|

### <a href=#Product name="Product">Product</a>

First included in: ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Product attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionType name="DimensionType">DimensionType</a>

First included in: ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalUnitSymbol name="PhysicalUnitSymbol">PhysicalUnitSymbol</a>

First included in: ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalDepth name="PhysicalDepth">PhysicalDepth</a>

First included in: ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalDepth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalHeight name="PhysicalHeight">PhysicalHeight</a>

First included in: ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalHeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalWeight name="PhysicalWeight">PhysicalWeight</a>

First included in: ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalWidth name="PhysicalWidth">PhysicalWidth</a>

First included in: ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalWidth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MassUnitSymbol name="MassUnitSymbol">MassUnitSymbol</a>

First included in: ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MassUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LengthUnitSymbol name="LengthUnitSymbol">LengthUnitSymbol</a>

First included in: ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LengthUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VolumeUnitSymbol name="VolumeUnitSymbol">VolumeUnitSymbol</a>

First included in: ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VolumeUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductNumber name="ProductNumber">ProductNumber</a>

First included in: ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProductV2RelationshipId name="Relationship_ProductV2RelationshipId">Relationship_ProductV2RelationshipId</a>

First included in: ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductV2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MassUnitOfMeasureRelationshipId name="Relationship_MassUnitOfMeasureRelationshipId">Relationship_MassUnitOfMeasureRelationshipId</a>

First included in: ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MassUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LengthUnitOfMeasureRelationshipId name="Relationship_LengthUnitOfMeasureRelationshipId">Relationship_LengthUnitOfMeasureRelationshipId</a>

First included in: ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LengthUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_VolumeUnitOfMeasureRelationshipId name="Relationship_VolumeUnitOfMeasureRelationshipId">Relationship_VolumeUnitOfMeasureRelationshipId</a>

First included in: ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VolumeUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PhysicalUnitOfMeasureRelationshipId name="Relationship_PhysicalUnitOfMeasureRelationshipId">Relationship_PhysicalUnitOfMeasureRelationshipId</a>

First included in: ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PhysicalUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_EcoResPhysicalProductDimensionsRelationshipId name="BackingTable_EcoResPhysicalProductDimensionsRelationshipId">BackingTable_EcoResPhysicalProductDimensionsRelationshipId</a>

First included in: ProductInformationManagement/EcoResPhysicalProductDimensionDetailsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResPhysicalProductDimensionsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResPhysicalProductDimensions.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResPhysicalProductDimensions.cdm.json/EcoResPhysicalProductDimensions</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResPhysicalProductDimensions.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
