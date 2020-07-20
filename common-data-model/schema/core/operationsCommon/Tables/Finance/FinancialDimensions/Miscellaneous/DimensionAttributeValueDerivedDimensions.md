---
title: DimensionAttributeValueDerivedDimensions in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Derived dimensions values in Miscellaneous(DimensionAttributeValueDerivedDimensions)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FinancialDimensions/Miscellaneous/DimensionAttributeValueDerivedDimensions.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DimensionAttributeValueDerivedDimensions/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

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
|[RecId](#RecId)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[DimensionAttribute](#DimensionAttribute)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[DimensionAttributeValue](#DimensionAttributeValue)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[DerivedDimensionAttributeValue1](#DerivedDimensionAttributeValue1)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[DerivedDimensionAttributeValue2](#DerivedDimensionAttributeValue2)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[DerivedDimensionAttributeValue3](#DerivedDimensionAttributeValue3)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[DerivedDimensionAttributeValue4](#DerivedDimensionAttributeValue4)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[DerivedDimensionAttributeValue5](#DerivedDimensionAttributeValue5)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[DerivedDimensionAttributeValue6](#DerivedDimensionAttributeValue6)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[DerivedDimensionAttributeValue7](#DerivedDimensionAttributeValue7)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[DerivedDimensionAttributeValue8](#DerivedDimensionAttributeValue8)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[DerivedDimensionAttributeValue9](#DerivedDimensionAttributeValue9)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[DerivedDimensionAttributeValue10](#DerivedDimensionAttributeValue10)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[DefaultDimension](#DefaultDimension)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[Relationship_DimensionAttributeRelationshipId](#Relationship_DimensionAttributeRelationshipId)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[Relationship_DrivingDimensionAttributeValueRelationshipId](#Relationship_DrivingDimensionAttributeValueRelationshipId)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[Relationship_DerivedDimensionAttributeValue1RelationshipId](#Relationship_DerivedDimensionAttributeValue1RelationshipId)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[Relationship_DerivedDimensionAttributeValue2RelationshipId](#Relationship_DerivedDimensionAttributeValue2RelationshipId)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[Relationship_DerivedDimensionAttributeValue3RelationshipId](#Relationship_DerivedDimensionAttributeValue3RelationshipId)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[Relationship_DerivedDimensionAttributeValue4RelationshipId](#Relationship_DerivedDimensionAttributeValue4RelationshipId)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[Relationship_DerivedDimensionAttributeValue5RelationshipId](#Relationship_DerivedDimensionAttributeValue5RelationshipId)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[Relationship_DerivedDimensionAttributeValue6RelationshipId](#Relationship_DerivedDimensionAttributeValue6RelationshipId)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[Relationship_DerivedDimensionAttributeValue7RelationshipId](#Relationship_DerivedDimensionAttributeValue7RelationshipId)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[Relationship_DerivedDimensionAttributeValue8RelationshipId](#Relationship_DerivedDimensionAttributeValue8RelationshipId)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[Relationship_DerivedDimensionAttributeValue9RelationshipId](#Relationship_DerivedDimensionAttributeValue9RelationshipId)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[Relationship_DerivedDimensionAttributeValue10RelationshipId](#Relationship_DerivedDimensionAttributeValue10RelationshipId)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="DimensionAttributeValueDerivedDimensions.md" target="_blank">Miscellaneous/DimensionAttributeValueDerivedDimensions</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DimensionAttributeValueDerivedDimensions/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DimensionAttribute name="DimensionAttribute">DimensionAttribute</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionAttribute attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DimensionAttributeValue name="DimensionAttributeValue">DimensionAttributeValue</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionAttributeValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DerivedDimensionAttributeValue1 name="DerivedDimensionAttributeValue1">DerivedDimensionAttributeValue1</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue1 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DerivedDimensionAttributeValue2 name="DerivedDimensionAttributeValue2">DerivedDimensionAttributeValue2</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue2 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DerivedDimensionAttributeValue3 name="DerivedDimensionAttributeValue3">DerivedDimensionAttributeValue3</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue3 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DerivedDimensionAttributeValue4 name="DerivedDimensionAttributeValue4">DerivedDimensionAttributeValue4</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue4 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DerivedDimensionAttributeValue5 name="DerivedDimensionAttributeValue5">DerivedDimensionAttributeValue5</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue5 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DerivedDimensionAttributeValue6 name="DerivedDimensionAttributeValue6">DerivedDimensionAttributeValue6</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue6 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DerivedDimensionAttributeValue7 name="DerivedDimensionAttributeValue7">DerivedDimensionAttributeValue7</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue7 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DerivedDimensionAttributeValue8 name="DerivedDimensionAttributeValue8">DerivedDimensionAttributeValue8</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue8 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DerivedDimensionAttributeValue9 name="DerivedDimensionAttributeValue9">DerivedDimensionAttributeValue9</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue9 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DerivedDimensionAttributeValue10 name="DerivedDimensionAttributeValue10">DerivedDimensionAttributeValue10</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DerivedDimensionAttributeValue10 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_DimensionAttributeRelationshipId name="Relationship_DimensionAttributeRelationshipId">Relationship_DimensionAttributeRelationshipId</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionAttributeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/DimensionAttribute.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Reference/DimensionAttribute.cdm.json/DimensionAttribute</a></td><td><a href="../Reference/DimensionAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DrivingDimensionAttributeValueRelationshipId name="Relationship_DrivingDimensionAttributeValueRelationshipId">Relationship_DrivingDimensionAttributeValueRelationshipId</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DrivingDimensionAttributeValueRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/DimensionAttributeValue.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValue.cdm.json/DimensionAttributeValue</a></td><td><a href="../Main/DimensionAttributeValue.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DerivedDimensionAttributeValue1RelationshipId name="Relationship_DerivedDimensionAttributeValue1RelationshipId">Relationship_DerivedDimensionAttributeValue1RelationshipId</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimensionAttributeValue1RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/DimensionAttributeValue.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValue.cdm.json/DimensionAttributeValue</a></td><td><a href="../Main/DimensionAttributeValue.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DerivedDimensionAttributeValue2RelationshipId name="Relationship_DerivedDimensionAttributeValue2RelationshipId">Relationship_DerivedDimensionAttributeValue2RelationshipId</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimensionAttributeValue2RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/DimensionAttributeValue.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValue.cdm.json/DimensionAttributeValue</a></td><td><a href="../Main/DimensionAttributeValue.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DerivedDimensionAttributeValue3RelationshipId name="Relationship_DerivedDimensionAttributeValue3RelationshipId">Relationship_DerivedDimensionAttributeValue3RelationshipId</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimensionAttributeValue3RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/DimensionAttributeValue.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValue.cdm.json/DimensionAttributeValue</a></td><td><a href="../Main/DimensionAttributeValue.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DerivedDimensionAttributeValue4RelationshipId name="Relationship_DerivedDimensionAttributeValue4RelationshipId">Relationship_DerivedDimensionAttributeValue4RelationshipId</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimensionAttributeValue4RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/DimensionAttributeValue.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValue.cdm.json/DimensionAttributeValue</a></td><td><a href="../Main/DimensionAttributeValue.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DerivedDimensionAttributeValue5RelationshipId name="Relationship_DerivedDimensionAttributeValue5RelationshipId">Relationship_DerivedDimensionAttributeValue5RelationshipId</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimensionAttributeValue5RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/DimensionAttributeValue.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValue.cdm.json/DimensionAttributeValue</a></td><td><a href="../Main/DimensionAttributeValue.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DerivedDimensionAttributeValue6RelationshipId name="Relationship_DerivedDimensionAttributeValue6RelationshipId">Relationship_DerivedDimensionAttributeValue6RelationshipId</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimensionAttributeValue6RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/DimensionAttributeValue.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValue.cdm.json/DimensionAttributeValue</a></td><td><a href="../Main/DimensionAttributeValue.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DerivedDimensionAttributeValue7RelationshipId name="Relationship_DerivedDimensionAttributeValue7RelationshipId">Relationship_DerivedDimensionAttributeValue7RelationshipId</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimensionAttributeValue7RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/DimensionAttributeValue.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValue.cdm.json/DimensionAttributeValue</a></td><td><a href="../Main/DimensionAttributeValue.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DerivedDimensionAttributeValue8RelationshipId name="Relationship_DerivedDimensionAttributeValue8RelationshipId">Relationship_DerivedDimensionAttributeValue8RelationshipId</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimensionAttributeValue8RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/DimensionAttributeValue.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValue.cdm.json/DimensionAttributeValue</a></td><td><a href="../Main/DimensionAttributeValue.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DerivedDimensionAttributeValue9RelationshipId name="Relationship_DerivedDimensionAttributeValue9RelationshipId">Relationship_DerivedDimensionAttributeValue9RelationshipId</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimensionAttributeValue9RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/DimensionAttributeValue.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValue.cdm.json/DimensionAttributeValue</a></td><td><a href="../Main/DimensionAttributeValue.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DerivedDimensionAttributeValue10RelationshipId name="Relationship_DerivedDimensionAttributeValue10RelationshipId">Relationship_DerivedDimensionAttributeValue10RelationshipId</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DerivedDimensionAttributeValue10RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/DimensionAttributeValue.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValue.cdm.json/DimensionAttributeValue</a></td><td><a href="../Main/DimensionAttributeValue.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: Miscellaneous/DimensionAttributeValueDerivedDimensions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
