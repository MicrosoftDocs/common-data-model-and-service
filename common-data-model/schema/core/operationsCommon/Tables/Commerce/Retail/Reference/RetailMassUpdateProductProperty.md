---
title: RetailMassUpdateProductProperty - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailMassUpdateProductProperty

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Reference/RetailMassUpdateProductProperty.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailMassUpdateProductProperty/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailMassUpdateProductProperty.md" target="_blank">Reference/RetailMassUpdateProductProperty</a>|
|[DestinationFieldNum](#DestinationFieldNum)||<a href="RetailMassUpdateProductProperty.md" target="_blank">Reference/RetailMassUpdateProductProperty</a>|
|[DestinationTableNum](#DestinationTableNum)||<a href="RetailMassUpdateProductProperty.md" target="_blank">Reference/RetailMassUpdateProductProperty</a>|
|[FastTabRecID](#FastTabRecID)||<a href="RetailMassUpdateProductProperty.md" target="_blank">Reference/RetailMassUpdateProductProperty</a>|
|[ModuleInventPurchSales](#ModuleInventPurchSales)||<a href="RetailMassUpdateProductProperty.md" target="_blank">Reference/RetailMassUpdateProductProperty</a>|
|[PropertyDescription](#PropertyDescription)||<a href="RetailMassUpdateProductProperty.md" target="_blank">Reference/RetailMassUpdateProductProperty</a>|
|[Selection](#Selection)||<a href="RetailMassUpdateProductProperty.md" target="_blank">Reference/RetailMassUpdateProductProperty</a>|
|[SourceFieldNum](#SourceFieldNum)||<a href="RetailMassUpdateProductProperty.md" target="_blank">Reference/RetailMassUpdateProductProperty</a>|
|[Relationship_RetailMassUpdateProductFastTabRelationshipId](#Relationship_RetailMassUpdateProductFastTabRelationshipId)||<a href="RetailMassUpdateProductProperty.md" target="_blank">Reference/RetailMassUpdateProductProperty</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Reference/RetailMassUpdateProductProperty (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailMassUpdateProductProperty/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DestinationFieldNum name="DestinationFieldNum">DestinationFieldNum</a>

First included in: Reference/RetailMassUpdateProductProperty (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationFieldNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DestinationTableNum name="DestinationTableNum">DestinationTableNum</a>

First included in: Reference/RetailMassUpdateProductProperty (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationTableNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FastTabRecID name="FastTabRecID">FastTabRecID</a>

First included in: Reference/RetailMassUpdateProductProperty (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FastTabRecID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ModuleInventPurchSales name="ModuleInventPurchSales">ModuleInventPurchSales</a>

First included in: Reference/RetailMassUpdateProductProperty (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModuleInventPurchSales attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#PropertyDescription name="PropertyDescription">PropertyDescription</a>

First included in: Reference/RetailMassUpdateProductProperty (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PropertyDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Selection name="Selection">Selection</a>

First included in: Reference/RetailMassUpdateProductProperty (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Selection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SourceFieldNum name="SourceFieldNum">SourceFieldNum</a>

First included in: Reference/RetailMassUpdateProductProperty (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceFieldNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_RetailMassUpdateProductFastTabRelationshipId name="Relationship_RetailMassUpdateProductFastTabRelationshipId">Relationship_RetailMassUpdateProductFastTabRelationshipId</a>

First included in: Reference/RetailMassUpdateProductProperty (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailMassUpdateProductFastTabRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailMassUpdateProductFastTab.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Reference/RetailMassUpdateProductFastTab.cdm.json/RetailMassUpdateProductFastTab</a></td><td><a href="RetailMassUpdateProductFastTab.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
