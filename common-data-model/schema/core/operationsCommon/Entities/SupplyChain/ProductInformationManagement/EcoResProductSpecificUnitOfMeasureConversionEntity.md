---
title: EcoResProductSpecificUnitOfMeasureConversionEntity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Product specific unit conversions in ProductInformationManagement(EcoResProductSpecificUnitOfMeasureConversionEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product specific unit conversions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Denominator](#Denominator)||<a href="EcoResProductSpecificUnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity</a>|
|[Factor](#Factor)||<a href="EcoResProductSpecificUnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity</a>|
|[FromUnitOfMeasureRecId](#FromUnitOfMeasureRecId)||<a href="EcoResProductSpecificUnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity</a>|
|[InnerOffset](#InnerOffset)||<a href="EcoResProductSpecificUnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity</a>|
|[Numerator](#Numerator)||<a href="EcoResProductSpecificUnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity</a>|
|[OuterOffset](#OuterOffset)||<a href="EcoResProductSpecificUnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity</a>|
|[ProductRecId](#ProductRecId)||<a href="EcoResProductSpecificUnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity</a>|
|[Rounding](#Rounding)||<a href="EcoResProductSpecificUnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity</a>|
|[ToUnitOfMeasureRecId](#ToUnitOfMeasureRecId)||<a href="EcoResProductSpecificUnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity</a>|
|[ProductNumber](#ProductNumber)||<a href="EcoResProductSpecificUnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity</a>|
|[FromUnitSymbol](#FromUnitSymbol)||<a href="EcoResProductSpecificUnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity</a>|
|[ToUnitSymbol](#ToUnitSymbol)||<a href="EcoResProductSpecificUnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity</a>|
|[Relationship_ToUnitSymbolRelationshipId](#Relationship_ToUnitSymbolRelationshipId)||<a href="EcoResProductSpecificUnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity</a>|
|[Relationship_FromUnitSymbolRelationshipId](#Relationship_FromUnitSymbolRelationshipId)||<a href="EcoResProductSpecificUnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity</a>|
|[Relationship_EveryProductRelationshipId](#Relationship_EveryProductRelationshipId)||<a href="EcoResProductSpecificUnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity</a>|

### <a href=#Denominator name="Denominator">Denominator</a>

First included in: ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Denominator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Factor name="Factor">Factor</a>

First included in: ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Factor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromUnitOfMeasureRecId name="FromUnitOfMeasureRecId">FromUnitOfMeasureRecId</a>

First included in: ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromUnitOfMeasureRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InnerOffset name="InnerOffset">InnerOffset</a>

First included in: ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InnerOffset attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Numerator name="Numerator">Numerator</a>

First included in: ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Numerator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OuterOffset name="OuterOffset">OuterOffset</a>

First included in: ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OuterOffset attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductRecId name="ProductRecId">ProductRecId</a>

First included in: ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Rounding name="Rounding">Rounding</a>

First included in: ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Rounding attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToUnitOfMeasureRecId name="ToUnitOfMeasureRecId">ToUnitOfMeasureRecId</a>

First included in: ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToUnitOfMeasureRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductNumber name="ProductNumber">ProductNumber</a>

First included in: ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity (this entity)  

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

### <a href=#FromUnitSymbol name="FromUnitSymbol">FromUnitSymbol</a>

First included in: ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToUnitSymbol name="ToUnitSymbol">ToUnitSymbol</a>

First included in: ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ToUnitSymbolRelationshipId name="Relationship_ToUnitSymbolRelationshipId">Relationship_ToUnitSymbolRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ToUnitSymbolRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_FromUnitSymbolRelationshipId name="Relationship_FromUnitSymbolRelationshipId">Relationship_FromUnitSymbolRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FromUnitSymbolRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_EveryProductRelationshipId name="Relationship_EveryProductRelationshipId">Relationship_EveryProductRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductSpecificUnitOfMeasureConversionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EveryProductRelationshipId attribute are listed below.</summary>

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
