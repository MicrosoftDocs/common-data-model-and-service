---
title: DerivedDimensionAttributeValuesEntity in FinancialDimensions - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Derived dimensions values in FinancialDimensions(DerivedDimensionAttributeValuesEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/FinancialDimensions/DerivedDimensionAttributeValuesEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimensions values</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DrivingDimensionAttributeName](#DrivingDimensionAttributeName)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DrivingDimensionAttributeValue](#DrivingDimensionAttributeValue)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeName1](#DerivedDimensionAttributeName1)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValue1](#DerivedDimensionAttributeValue1)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeName2](#DerivedDimensionAttributeName2)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValue2](#DerivedDimensionAttributeValue2)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeName3](#DerivedDimensionAttributeName3)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValue3](#DerivedDimensionAttributeValue3)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeName4](#DerivedDimensionAttributeName4)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValue4](#DerivedDimensionAttributeValue4)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeName5](#DerivedDimensionAttributeName5)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValue5](#DerivedDimensionAttributeValue5)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeName6](#DerivedDimensionAttributeName6)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValue6](#DerivedDimensionAttributeValue6)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeName7](#DerivedDimensionAttributeName7)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValue7](#DerivedDimensionAttributeValue7)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeName8](#DerivedDimensionAttributeName8)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValue8](#DerivedDimensionAttributeValue8)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeName9](#DerivedDimensionAttributeName9)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValue9](#DerivedDimensionAttributeValue9)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeName10](#DerivedDimensionAttributeName10)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValue10](#DerivedDimensionAttributeValue10)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DrivingDimensionAttribute](#DrivingDimensionAttribute)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DrivingDimensionAttributeValueRecId](#DrivingDimensionAttributeValueRecId)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValueRecId1](#DerivedDimensionAttributeValueRecId1)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValueRecId2](#DerivedDimensionAttributeValueRecId2)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValueRecId3](#DerivedDimensionAttributeValueRecId3)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValueRecId4](#DerivedDimensionAttributeValueRecId4)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValueRecId5](#DerivedDimensionAttributeValueRecId5)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValueRecId6](#DerivedDimensionAttributeValueRecId6)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValueRecId7](#DerivedDimensionAttributeValueRecId7)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValueRecId8](#DerivedDimensionAttributeValueRecId8)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValueRecId9](#DerivedDimensionAttributeValueRecId9)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[DerivedDimensionAttributeValueRecId10](#DerivedDimensionAttributeValueRecId10)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[Relationship_DrivingDimensionRelationshipId](#Relationship_DrivingDimensionRelationshipId)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[Relationship_DerivedDimension1RelationshipId](#Relationship_DerivedDimension1RelationshipId)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[Relationship_DerivedDimension2RelationshipId](#Relationship_DerivedDimension2RelationshipId)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[Relationship_DerivedDimension3RelationshipId](#Relationship_DerivedDimension3RelationshipId)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[Relationship_DerivedDimension4RelationshipId](#Relationship_DerivedDimension4RelationshipId)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[Relationship_DerivedDimension5RelationshipId](#Relationship_DerivedDimension5RelationshipId)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[Relationship_DerivedDimension6RelationshipId](#Relationship_DerivedDimension6RelationshipId)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[Relationship_DerivedDimension7RelationshipId](#Relationship_DerivedDimension7RelationshipId)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[Relationship_DerivedDimension8RelationshipId](#Relationship_DerivedDimension8RelationshipId)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[Relationship_DerivedDimension9RelationshipId](#Relationship_DerivedDimension9RelationshipId)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[Relationship_DerivedDimension10RelationshipId](#Relationship_DerivedDimension10RelationshipId)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|
|[BackingTable_DimensionAttributeValueDerivedDimensionsRelationshipId](#BackingTable_DimensionAttributeValueDerivedDimensionsRelationshipId)||<a href="DerivedDimensionAttributeValuesEntity.md" target="_blank">FinancialDimensions/DerivedDimensionAttributeValuesEntity</a>|

### <a href=#DrivingDimensionAttributeName name="DrivingDimensionAttributeName">DrivingDimensionAttributeName</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Driving dimension attribute name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DrivingDimensionAttributeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Driving dimension attribute name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DrivingDimensionAttributeValue name="DrivingDimensionAttributeValue">DrivingDimensionAttributeValue</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Driving dimension attribute value</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DrivingDimensionAttributeValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Driving dimension attribute value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeName1 name="DerivedDimensionAttributeName1">DerivedDimensionAttributeName1</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute name 1</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeName1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute name 1</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValue1 name="DerivedDimensionAttributeValue1">DerivedDimensionAttributeValue1</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute value 1</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute value 1</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeName2 name="DerivedDimensionAttributeName2">DerivedDimensionAttributeName2</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute name 2</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeName2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute name 2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValue2 name="DerivedDimensionAttributeValue2">DerivedDimensionAttributeValue2</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute value 2</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute value 2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeName3 name="DerivedDimensionAttributeName3">DerivedDimensionAttributeName3</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute name 3</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeName3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute name 3</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValue3 name="DerivedDimensionAttributeValue3">DerivedDimensionAttributeValue3</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute value 3</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute value 3</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeName4 name="DerivedDimensionAttributeName4">DerivedDimensionAttributeName4</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute name 4</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeName4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute name 4</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValue4 name="DerivedDimensionAttributeValue4">DerivedDimensionAttributeValue4</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute value 4</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute value 4</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeName5 name="DerivedDimensionAttributeName5">DerivedDimensionAttributeName5</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute name 5</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeName5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute name 5</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValue5 name="DerivedDimensionAttributeValue5">DerivedDimensionAttributeValue5</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute value 5</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute value 5</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeName6 name="DerivedDimensionAttributeName6">DerivedDimensionAttributeName6</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute name 6</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeName6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute name 6</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValue6 name="DerivedDimensionAttributeValue6">DerivedDimensionAttributeValue6</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute value 6</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute value 6</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeName7 name="DerivedDimensionAttributeName7">DerivedDimensionAttributeName7</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute name 7</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeName7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute name 7</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValue7 name="DerivedDimensionAttributeValue7">DerivedDimensionAttributeValue7</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute value 7</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute value 7</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeName8 name="DerivedDimensionAttributeName8">DerivedDimensionAttributeName8</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute name 8</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeName8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute name 8</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValue8 name="DerivedDimensionAttributeValue8">DerivedDimensionAttributeValue8</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute value 8</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute value 8</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeName9 name="DerivedDimensionAttributeName9">DerivedDimensionAttributeName9</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute name 9</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeName9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute name 9</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValue9 name="DerivedDimensionAttributeValue9">DerivedDimensionAttributeValue9</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute value 9</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute value 9</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeName10 name="DerivedDimensionAttributeName10">DerivedDimensionAttributeName10</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute name 10</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeName10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute name 10</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValue10 name="DerivedDimensionAttributeValue10">DerivedDimensionAttributeValue10</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Derived dimension attribute value 10</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Derived dimension attribute value 10</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DrivingDimensionAttribute name="DrivingDimensionAttribute">DrivingDimensionAttribute</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DrivingDimensionAttribute attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DrivingDimensionAttributeValueRecId name="DrivingDimensionAttributeValueRecId">DrivingDimensionAttributeValueRecId</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DrivingDimensionAttributeValueRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValueRecId1 name="DerivedDimensionAttributeValueRecId1">DerivedDimensionAttributeValueRecId1</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValueRecId1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValueRecId2 name="DerivedDimensionAttributeValueRecId2">DerivedDimensionAttributeValueRecId2</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValueRecId2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValueRecId3 name="DerivedDimensionAttributeValueRecId3">DerivedDimensionAttributeValueRecId3</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValueRecId3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValueRecId4 name="DerivedDimensionAttributeValueRecId4">DerivedDimensionAttributeValueRecId4</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValueRecId4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValueRecId5 name="DerivedDimensionAttributeValueRecId5">DerivedDimensionAttributeValueRecId5</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValueRecId5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValueRecId6 name="DerivedDimensionAttributeValueRecId6">DerivedDimensionAttributeValueRecId6</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValueRecId6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValueRecId7 name="DerivedDimensionAttributeValueRecId7">DerivedDimensionAttributeValueRecId7</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValueRecId7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValueRecId8 name="DerivedDimensionAttributeValueRecId8">DerivedDimensionAttributeValueRecId8</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValueRecId8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValueRecId9 name="DerivedDimensionAttributeValueRecId9">DerivedDimensionAttributeValueRecId9</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValueRecId9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DerivedDimensionAttributeValueRecId10 name="DerivedDimensionAttributeValueRecId10">DerivedDimensionAttributeValueRecId10</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValueRecId10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DrivingDimensionRelationshipId name="Relationship_DrivingDimensionRelationshipId">Relationship_DrivingDimensionRelationshipId</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DrivingDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DerivedDimension1RelationshipId name="Relationship_DerivedDimension1RelationshipId">Relationship_DerivedDimension1RelationshipId</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimension1RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DerivedDimension2RelationshipId name="Relationship_DerivedDimension2RelationshipId">Relationship_DerivedDimension2RelationshipId</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimension2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DerivedDimension3RelationshipId name="Relationship_DerivedDimension3RelationshipId">Relationship_DerivedDimension3RelationshipId</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimension3RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DerivedDimension4RelationshipId name="Relationship_DerivedDimension4RelationshipId">Relationship_DerivedDimension4RelationshipId</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimension4RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DerivedDimension5RelationshipId name="Relationship_DerivedDimension5RelationshipId">Relationship_DerivedDimension5RelationshipId</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimension5RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DerivedDimension6RelationshipId name="Relationship_DerivedDimension6RelationshipId">Relationship_DerivedDimension6RelationshipId</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimension6RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DerivedDimension7RelationshipId name="Relationship_DerivedDimension7RelationshipId">Relationship_DerivedDimension7RelationshipId</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimension7RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DerivedDimension8RelationshipId name="Relationship_DerivedDimension8RelationshipId">Relationship_DerivedDimension8RelationshipId</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimension8RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DerivedDimension9RelationshipId name="Relationship_DerivedDimension9RelationshipId">Relationship_DerivedDimension9RelationshipId</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimension9RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DerivedDimension10RelationshipId name="Relationship_DerivedDimension10RelationshipId">Relationship_DerivedDimension10RelationshipId</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimension10RelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_DimensionAttributeValueDerivedDimensionsRelationshipId name="BackingTable_DimensionAttributeValueDerivedDimensionsRelationshipId">BackingTable_DimensionAttributeValueDerivedDimensionsRelationshipId</a>

First included in: FinancialDimensions/DerivedDimensionAttributeValuesEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_DimensionAttributeValueDerivedDimensionsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FinancialDimensions/Miscellaneous/DimensionAttributeValueDerivedDimensions.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Miscellaneous/DimensionAttributeValueDerivedDimensions.cdm.json/DimensionAttributeValueDerivedDimensions</a></td><td><a href="../../../Tables/Finance/FinancialDimensions/Miscellaneous/DimensionAttributeValueDerivedDimensions.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
