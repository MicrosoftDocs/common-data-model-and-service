---
title: RetailKeyboardMappingTrans - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailKeyboardMappingTrans

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Parameter/RetailKeyboardMappingTrans.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailKeyboardMappingTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailKeyboardMappingTrans.md" target="_blank">Parameter/RetailKeyboardMappingTrans</a>|
|[action](#action)||<a href="RetailKeyboardMappingTrans.md" target="_blank">Parameter/RetailKeyboardMappingTrans</a>|
|[actionProperty](#actionProperty)||<a href="RetailKeyboardMappingTrans.md" target="_blank">Parameter/RetailKeyboardMappingTrans</a>|
|[ASCIIValue](#ASCIIValue)||<a href="RetailKeyboardMappingTrans.md" target="_blank">Parameter/RetailKeyboardMappingTrans</a>|
|[keyboardMappingId](#keyboardMappingId)||<a href="RetailKeyboardMappingTrans.md" target="_blank">Parameter/RetailKeyboardMappingTrans</a>|
|[keyChar](#keyChar)||<a href="RetailKeyboardMappingTrans.md" target="_blank">Parameter/RetailKeyboardMappingTrans</a>|
|[Relationship_RetailKeyboardMappingTableRelationshipId](#Relationship_RetailKeyboardMappingTableRelationshipId)||<a href="RetailKeyboardMappingTrans.md" target="_blank">Parameter/RetailKeyboardMappingTrans</a>|
|[Relationship_RetailOperationsRelationshipId](#Relationship_RetailOperationsRelationshipId)||<a href="RetailKeyboardMappingTrans.md" target="_blank">Parameter/RetailKeyboardMappingTrans</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/RetailKeyboardMappingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailKeyboardMappingTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#action name="action">action</a>

First included in: Parameter/RetailKeyboardMappingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the action attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#actionProperty name="actionProperty">actionProperty</a>

First included in: Parameter/RetailKeyboardMappingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the actionProperty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ASCIIValue name="ASCIIValue">ASCIIValue</a>

First included in: Parameter/RetailKeyboardMappingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ASCIIValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#keyboardMappingId name="keyboardMappingId">keyboardMappingId</a>

First included in: Parameter/RetailKeyboardMappingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the keyboardMappingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#keyChar name="keyChar">keyChar</a>

First included in: Parameter/RetailKeyboardMappingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the keyChar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailKeyboardMappingTableRelationshipId name="Relationship_RetailKeyboardMappingTableRelationshipId">Relationship_RetailKeyboardMappingTableRelationshipId</a>

First included in: Parameter/RetailKeyboardMappingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailKeyboardMappingTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailKeyboardMappingTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Parameter/RetailKeyboardMappingTable.cdm.json/RetailKeyboardMappingTable</a></td><td><a href="RetailKeyboardMappingTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailOperationsRelationshipId name="Relationship_RetailOperationsRelationshipId">Relationship_RetailOperationsRelationshipId</a>

First included in: Parameter/RetailKeyboardMappingTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailOperationsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailOperations.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Parameter/RetailOperations.cdm.json/RetailOperations</a></td><td><a href="RetailOperations.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
