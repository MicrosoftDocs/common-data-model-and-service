---
title: DimensionAttributeEntity in FinancialDimensions - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Financial dimensions in FinancialDimensions(DimensionAttributeEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/FinancialDimensions/DimensionAttributeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Financial dimensions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DimensionName](#DimensionName)||<a href="DimensionAttributeEntity.md" target="_blank">FinancialDimensions/DimensionAttributeEntity</a>|
|[ReportColumnName](#ReportColumnName)||<a href="DimensionAttributeEntity.md" target="_blank">FinancialDimensions/DimensionAttributeEntity</a>|
|[ViewName](#ViewName)||<a href="DimensionAttributeEntity.md" target="_blank">FinancialDimensions/DimensionAttributeEntity</a>|
|[DimensionAttributeRecId](#DimensionAttributeRecId)||<a href="DimensionAttributeEntity.md" target="_blank">FinancialDimensions/DimensionAttributeEntity</a>|
|[UseValuesFrom](#UseValuesFrom)||<a href="DimensionAttributeEntity.md" target="_blank">FinancialDimensions/DimensionAttributeEntity</a>|
|[DimensionValueMask](#DimensionValueMask)||<a href="DimensionAttributeEntity.md" target="_blank">FinancialDimensions/DimensionAttributeEntity</a>|
|[CopyValuesOnCreate](#CopyValuesOnCreate)||<a href="DimensionAttributeEntity.md" target="_blank">FinancialDimensions/DimensionAttributeEntity</a>|
|[GiveDerivedDimensionsPrecedence](#GiveDerivedDimensionsPrecedence)||<a href="DimensionAttributeEntity.md" target="_blank">FinancialDimensions/DimensionAttributeEntity</a>|
|[BalancingDimension_PSN](#BalancingDimension_PSN)||<a href="DimensionAttributeEntity.md" target="_blank">FinancialDimensions/DimensionAttributeEntity</a>|
|[IsBalancing_PSN](#IsBalancing_PSN)||<a href="DimensionAttributeEntity.md" target="_blank">FinancialDimensions/DimensionAttributeEntity</a>|
|[BackingTable_DimensionAttributeRelationshipId](#BackingTable_DimensionAttributeRelationshipId)||<a href="DimensionAttributeEntity.md" target="_blank">FinancialDimensions/DimensionAttributeEntity</a>|

### <a href=#DimensionName name="DimensionName">DimensionName</a>

First included in: FinancialDimensions/DimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dimension name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Dimension name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportColumnName name="ReportColumnName">ReportColumnName</a>

First included in: FinancialDimensions/DimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportColumnName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ViewName name="ViewName">ViewName</a>

First included in: FinancialDimensions/DimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionAttributeRecId name="DimensionAttributeRecId">DimensionAttributeRecId</a>

First included in: FinancialDimensions/DimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionAttributeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseValuesFrom name="UseValuesFrom">UseValuesFrom</a>

First included in: FinancialDimensions/DimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use values from</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseValuesFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use values from</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionValueMask name="DimensionValueMask">DimensionValueMask</a>

First included in: FinancialDimensions/DimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dimension value mask</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionValueMask attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Dimension value mask</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CopyValuesOnCreate name="CopyValuesOnCreate">CopyValuesOnCreate</a>

First included in: FinancialDimensions/DimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CopyValuesOnCreate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiveDerivedDimensionsPrecedence name="GiveDerivedDimensionsPrecedence">GiveDerivedDimensionsPrecedence</a>

First included in: FinancialDimensions/DimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiveDerivedDimensionsPrecedence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BalancingDimension_PSN name="BalancingDimension_PSN">BalancingDimension_PSN</a>

First included in: FinancialDimensions/DimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalancingDimension_PSN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBalancing_PSN name="IsBalancing_PSN">IsBalancing_PSN</a>

First included in: FinancialDimensions/DimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBalancing_PSN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_DimensionAttributeRelationshipId name="BackingTable_DimensionAttributeRelationshipId">BackingTable_DimensionAttributeRelationshipId</a>

First included in: FinancialDimensions/DimensionAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_DimensionAttributeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FinancialDimensions/Reference/DimensionAttribute.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Reference/DimensionAttribute.cdm.json/DimensionAttribute</a></td><td><a href="../../../Tables/Finance/FinancialDimensions/Reference/DimensionAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
