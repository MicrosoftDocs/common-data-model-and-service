---
title: RetailTillLayoutReportZoneEntity in BrickAndMortarStore - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# POS screen layout report zones in BrickAndMortarStore(RetailTillLayoutReportZoneEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/ChannelManagement/BrickAndMortarStore/RetailTillLayoutReportZoneEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>POS screen layout report zones</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ReportID](#ReportID)||<a href="RetailTillLayoutReportZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutReportZoneEntity</a>|
|[LayoutId](#LayoutId)||<a href="RetailTillLayoutReportZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutReportZoneEntity</a>|
|[ZoneId](#ZoneId)||<a href="RetailTillLayoutReportZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutReportZoneEntity</a>|
|[DeviceType](#DeviceType)||<a href="RetailTillLayoutReportZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutReportZoneEntity</a>|
|[LayoutSizeId](#LayoutSizeId)||<a href="RetailTillLayoutReportZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutReportZoneEntity</a>|
|[Relationship_RetailTillLayoutEntityRelationshipId](#Relationship_RetailTillLayoutEntityRelationshipId)||<a href="RetailTillLayoutReportZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutReportZoneEntity</a>|
|[Relationship_RetailTillLayoutZoneEntityRelationshipId](#Relationship_RetailTillLayoutZoneEntityRelationshipId)||<a href="RetailTillLayoutReportZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutReportZoneEntity</a>|
|[Relationship_RetailTillLayoutSizeEntityRelationshipId](#Relationship_RetailTillLayoutSizeEntityRelationshipId)||<a href="RetailTillLayoutReportZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutReportZoneEntity</a>|
|[BackingTable_RetailTillLayoutReportZoneRelationshipId](#BackingTable_RetailTillLayoutReportZoneRelationshipId)||<a href="RetailTillLayoutReportZoneEntity.md" target="_blank">BrickAndMortarStore/RetailTillLayoutReportZoneEntity</a>|

### <a href=#ReportID name="ReportID">ReportID</a>

First included in: BrickAndMortarStore/RetailTillLayoutReportZoneEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LayoutId name="LayoutId">LayoutId</a>

First included in: BrickAndMortarStore/RetailTillLayoutReportZoneEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailTillLayoutReportZoneEntity (this entity)  

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

First included in: BrickAndMortarStore/RetailTillLayoutReportZoneEntity (this entity)  

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

### <a href=#LayoutSizeId name="LayoutSizeId">LayoutSizeId</a>

First included in: BrickAndMortarStore/RetailTillLayoutReportZoneEntity (this entity)  

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

### <a href=#Relationship_RetailTillLayoutEntityRelationshipId name="Relationship_RetailTillLayoutEntityRelationshipId">Relationship_RetailTillLayoutEntityRelationshipId</a>

First included in: BrickAndMortarStore/RetailTillLayoutReportZoneEntity (this entity)  

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

### <a href=#Relationship_RetailTillLayoutZoneEntityRelationshipId name="Relationship_RetailTillLayoutZoneEntityRelationshipId">Relationship_RetailTillLayoutZoneEntityRelationshipId</a>

First included in: BrickAndMortarStore/RetailTillLayoutReportZoneEntity (this entity)  

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

### <a href=#Relationship_RetailTillLayoutSizeEntityRelationshipId name="Relationship_RetailTillLayoutSizeEntityRelationshipId">Relationship_RetailTillLayoutSizeEntityRelationshipId</a>

First included in: BrickAndMortarStore/RetailTillLayoutReportZoneEntity (this entity)  

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

### <a href=#BackingTable_RetailTillLayoutReportZoneRelationshipId name="BackingTable_RetailTillLayoutReportZoneRelationshipId">BackingTable_RetailTillLayoutReportZoneRelationshipId</a>

First included in: BrickAndMortarStore/RetailTillLayoutReportZoneEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTillLayoutReportZoneRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailTillLayoutReportZone.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailTillLayoutReportZone.cdm.json/RetailTillLayoutReportZone</a></td><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailTillLayoutReportZone.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
