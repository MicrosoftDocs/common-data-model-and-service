---
title: RetailKeyboardMappingCodeEntity in BrickAndMortarStore - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Keyboard mapping in BrickAndMortarStore(RetailKeyboardMappingCodeEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/ChannelManagement/BrickAndMortarStore/RetailKeyboardMappingCodeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Keyboard mapping</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Operation](#Operation)||<a href="RetailKeyboardMappingCodeEntity.md" target="_blank">BrickAndMortarStore/RetailKeyboardMappingCodeEntity</a>|
|[ActionProperty](#ActionProperty)||<a href="RetailKeyboardMappingCodeEntity.md" target="_blank">BrickAndMortarStore/RetailKeyboardMappingCodeEntity</a>|
|[AsciiValue](#AsciiValue)||<a href="RetailKeyboardMappingCodeEntity.md" target="_blank">BrickAndMortarStore/RetailKeyboardMappingCodeEntity</a>|
|[KeyboardMappingGroup](#KeyboardMappingGroup)||<a href="RetailKeyboardMappingCodeEntity.md" target="_blank">BrickAndMortarStore/RetailKeyboardMappingCodeEntity</a>|
|[KeyCharacter](#KeyCharacter)||<a href="RetailKeyboardMappingCodeEntity.md" target="_blank">BrickAndMortarStore/RetailKeyboardMappingCodeEntity</a>|
|[BackingTable_RetailKeyboardMappingTransRelationshipId](#BackingTable_RetailKeyboardMappingTransRelationshipId)||<a href="RetailKeyboardMappingCodeEntity.md" target="_blank">BrickAndMortarStore/RetailKeyboardMappingCodeEntity</a>|

### <a href=#Operation name="Operation">Operation</a>

First included in: BrickAndMortarStore/RetailKeyboardMappingCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Operation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActionProperty name="ActionProperty">ActionProperty</a>

First included in: BrickAndMortarStore/RetailKeyboardMappingCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionProperty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AsciiValue name="AsciiValue">AsciiValue</a>

First included in: BrickAndMortarStore/RetailKeyboardMappingCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AsciiValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KeyboardMappingGroup name="KeyboardMappingGroup">KeyboardMappingGroup</a>

First included in: BrickAndMortarStore/RetailKeyboardMappingCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyboardMappingGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KeyCharacter name="KeyCharacter">KeyCharacter</a>

First included in: BrickAndMortarStore/RetailKeyboardMappingCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyCharacter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailKeyboardMappingTransRelationshipId name="BackingTable_RetailKeyboardMappingTransRelationshipId">BackingTable_RetailKeyboardMappingTransRelationshipId</a>

First included in: BrickAndMortarStore/RetailKeyboardMappingCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailKeyboardMappingTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Parameter/RetailKeyboardMappingTrans.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Parameter/RetailKeyboardMappingTrans.cdm.json/RetailKeyboardMappingTrans</a></td><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Parameter/RetailKeyboardMappingTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
