---
title: RetailTillLayoutButtonGridZoneEntity in BrickAndMortarStore - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# POS screen layout button grid zones in BrickAndMortarStore(RetailTillLayoutButtonGridZoneEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/ChannelManagement/BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>POS screen layout button grid zones</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[LayoutId](#LayoutId)||<a href="RetailTillLayoutButtonGridZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity</a>|
|[ZoneId](#ZoneId)||<a href="RetailTillLayoutButtonGridZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity</a>|
|[DeviceType](#DeviceType)||<a href="RetailTillLayoutButtonGridZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity</a>|
|[ButtonGridId](#ButtonGridId)||<a href="RetailTillLayoutButtonGridZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity</a>|
|[LayoutSizeId](#LayoutSizeId)||<a href="RetailTillLayoutButtonGridZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity</a>|
|[Relationship_RetailTillLayoutZoneEntityRelationshipId](#Relationship_RetailTillLayoutZoneEntityRelationshipId)||<a href="RetailTillLayoutButtonGridZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity</a>|
|[Relationship_RetailTillLayoutEntityRelationshipId](#Relationship_RetailTillLayoutEntityRelationshipId)||<a href="RetailTillLayoutButtonGridZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity</a>|
|[Relationship_RetailButtonGridRelationshipId](#Relationship_RetailButtonGridRelationshipId)||<a href="RetailTillLayoutButtonGridZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity</a>|
|[Relationship_RetailTillLayoutSizeEntityRelationshipId](#Relationship_RetailTillLayoutSizeEntityRelationshipId)||<a href="RetailTillLayoutButtonGridZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity</a>|
|[BackingTable_RetailTillLayoutButtonGridZoneRelationshipId](#BackingTable_RetailTillLayoutButtonGridZoneRelationshipId)||<a href="RetailTillLayoutButtonGridZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity</a>|

### <a href=#LayoutId name="LayoutId">LayoutId</a>

First included in: BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LayoutId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZoneId name="ZoneId">ZoneId</a>

First included in: BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZoneId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeviceType name="DeviceType">DeviceType</a>

First included in: BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeviceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ButtonGridId name="ButtonGridId">ButtonGridId</a>

First included in: BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ButtonGridId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LayoutSizeId name="LayoutSizeId">LayoutSizeId</a>

First included in: BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LayoutSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTillLayoutZoneEntityRelationshipId name="Relationship_RetailTillLayoutZoneEntityRelationshipId">Relationship_RetailTillLayoutZoneEntityRelationshipId</a>

First included in: BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTillLayoutZoneEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailTillLayoutEntityRelationshipId name="Relationship_RetailTillLayoutEntityRelationshipId">Relationship_RetailTillLayoutEntityRelationshipId</a>

First included in: BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTillLayoutEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailButtonGridRelationshipId name="Relationship_RetailButtonGridRelationshipId">Relationship_RetailButtonGridRelationshipId</a>

First included in: BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailButtonGridRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailTillLayoutSizeEntityRelationshipId name="Relationship_RetailTillLayoutSizeEntityRelationshipId">Relationship_RetailTillLayoutSizeEntityRelationshipId</a>

First included in: BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTillLayoutSizeEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_RetailTillLayoutButtonGridZoneRelationshipId name="BackingTable_RetailTillLayoutButtonGridZoneRelationshipId">BackingTable_RetailTillLayoutButtonGridZoneRelationshipId</a>

First included in: BrickAndMortarStore/RetailTillLayoutButtonGridZoneEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTillLayoutButtonGridZoneRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailTillLayoutButtonGridZone.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailTillLayoutButtonGridZone.cdm.json/RetailTillLayoutButtonGridZone</a></td><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailTillLayoutButtonGridZone.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
