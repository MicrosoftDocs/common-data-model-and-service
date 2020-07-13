---
title: UnitOfMeasureConversionEntity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Unit conversions in ProductInformationManagement(UnitOfMeasureConversionEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/UnitOfMeasureConversionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unit conversions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Denominator](#Denominator)||<a href="UnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/UnitOfMeasureConversionEntity</a>|
|[Factor](#Factor)||<a href="UnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/UnitOfMeasureConversionEntity</a>|
|[FromUnitOfMeasureRecId](#FromUnitOfMeasureRecId)||<a href="UnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/UnitOfMeasureConversionEntity</a>|
|[InnerOffset](#InnerOffset)||<a href="UnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/UnitOfMeasureConversionEntity</a>|
|[Numerator](#Numerator)||<a href="UnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/UnitOfMeasureConversionEntity</a>|
|[OuterOffset](#OuterOffset)||<a href="UnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/UnitOfMeasureConversionEntity</a>|
|[Rounding](#Rounding)||<a href="UnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/UnitOfMeasureConversionEntity</a>|
|[ToUnitOfMeasureRecId](#ToUnitOfMeasureRecId)||<a href="UnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/UnitOfMeasureConversionEntity</a>|
|[FromUnitSymbol](#FromUnitSymbol)||<a href="UnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/UnitOfMeasureConversionEntity</a>|
|[ToUnitSymbol](#ToUnitSymbol)||<a href="UnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/UnitOfMeasureConversionEntity</a>|
|[Relationship_FromUnitOfMeasureRelationshipId](#Relationship_FromUnitOfMeasureRelationshipId)||<a href="UnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/UnitOfMeasureConversionEntity</a>|
|[Relationship_ToUnitOfMeasureRelationshipId](#Relationship_ToUnitOfMeasureRelationshipId)||<a href="UnitOfMeasureConversionEntity.md" target="_blank">ProductInformationManagement/UnitOfMeasureConversionEntity</a>|

### <a href=#Denominator name="Denominator">Denominator</a>

First included in: ProductInformationManagement/UnitOfMeasureConversionEntity (this entity)  

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

First included in: ProductInformationManagement/UnitOfMeasureConversionEntity (this entity)  

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

First included in: ProductInformationManagement/UnitOfMeasureConversionEntity (this entity)  

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

First included in: ProductInformationManagement/UnitOfMeasureConversionEntity (this entity)  

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

First included in: ProductInformationManagement/UnitOfMeasureConversionEntity (this entity)  

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

First included in: ProductInformationManagement/UnitOfMeasureConversionEntity (this entity)  

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

### <a href=#Rounding name="Rounding">Rounding</a>

First included in: ProductInformationManagement/UnitOfMeasureConversionEntity (this entity)  

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

First included in: ProductInformationManagement/UnitOfMeasureConversionEntity (this entity)  

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

### <a href=#FromUnitSymbol name="FromUnitSymbol">FromUnitSymbol</a>

First included in: ProductInformationManagement/UnitOfMeasureConversionEntity (this entity)  

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

First included in: ProductInformationManagement/UnitOfMeasureConversionEntity (this entity)  

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

### <a href=#Relationship_FromUnitOfMeasureRelationshipId name="Relationship_FromUnitOfMeasureRelationshipId">Relationship_FromUnitOfMeasureRelationshipId</a>

First included in: ProductInformationManagement/UnitOfMeasureConversionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FromUnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ToUnitOfMeasureRelationshipId name="Relationship_ToUnitOfMeasureRelationshipId">Relationship_ToUnitOfMeasureRelationshipId</a>

First included in: ProductInformationManagement/UnitOfMeasureConversionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ToUnitOfMeasureRelationshipId attribute are listed below.</summary>

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
