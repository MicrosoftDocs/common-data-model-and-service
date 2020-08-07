---
title: RetailTillLayoutReportZoneLegacy in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Reports in Miscellaneous(RetailTillLayoutReportZoneLegacy)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailTillLayoutReportZoneLegacy.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailTillLayoutReportZoneLegacy/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Retail layout zone base table</td></tr><tr><td>en</td><td>Reports</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailTillLayoutReportZoneLegacy.md" target="_blank">Miscellaneous/RetailTillLayoutReportZoneLegacy</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="RetailTillLayoutReportZoneLegacy.md" target="_blank">Miscellaneous/RetailTillLayoutReportZoneLegacy</a>|
|[LayoutId](#LayoutId)||<a href="RetailTillLayoutReportZoneLegacy.md" target="_blank">Miscellaneous/RetailTillLayoutReportZoneLegacy</a>|
|[Zone](#Zone)||<a href="RetailTillLayoutReportZoneLegacy.md" target="_blank">Miscellaneous/RetailTillLayoutReportZoneLegacy</a>|
|[LayoutSizeId](#LayoutSizeId)||<a href="RetailTillLayoutReportZoneLegacy.md" target="_blank">Miscellaneous/RetailTillLayoutReportZoneLegacy</a>|
|[ConfigurationLayoutId](#ConfigurationLayoutId)||<a href="RetailTillLayoutReportZoneLegacy.md" target="_blank">Miscellaneous/RetailTillLayoutReportZoneLegacy</a>|
|[MasterZoneReference](#MasterZoneReference)||<a href="RetailTillLayoutReportZoneLegacy.md" target="_blank">Miscellaneous/RetailTillLayoutReportZoneLegacy</a>|
|[Relationship_RetailTillLayoutRelationshipId](#Relationship_RetailTillLayoutRelationshipId)||<a href="RetailTillLayoutReportZoneLegacy.md" target="_blank">Miscellaneous/RetailTillLayoutReportZoneLegacy</a>|
|[Relationship_RetailTillLayoutZoneRelationshipId](#Relationship_RetailTillLayoutZoneRelationshipId)||<a href="RetailTillLayoutReportZoneLegacy.md" target="_blank">Miscellaneous/RetailTillLayoutReportZoneLegacy</a>|
|[Relationship_RetailTillLayoutSizeRelationshipId](#Relationship_RetailTillLayoutSizeRelationshipId)||<a href="RetailTillLayoutReportZoneLegacy.md" target="_blank">Miscellaneous/RetailTillLayoutReportZoneLegacy</a>|
|[Relationship_RetailTillLayoutZoneReferenceRelationshipId](#Relationship_RetailTillLayoutZoneReferenceRelationshipId)||<a href="RetailTillLayoutReportZoneLegacy.md" target="_blank">Miscellaneous/RetailTillLayoutReportZoneLegacy</a>|
|[Report](#Report)||<a href="RetailTillLayoutReportZoneLegacy.md" target="_blank">Miscellaneous/RetailTillLayoutReportZoneLegacy</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailTillLayoutReportZoneLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailTillLayoutReportZoneLegacy/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Miscellaneous/RetailTillLayoutReportZoneLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LayoutId name="LayoutId">LayoutId</a>

First included in: Miscellaneous/RetailTillLayoutReportZoneLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LayoutId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Zone name="Zone">Zone</a>

First included in: Miscellaneous/RetailTillLayoutReportZoneLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Zone attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LayoutSizeId name="LayoutSizeId">LayoutSizeId</a>

First included in: Miscellaneous/RetailTillLayoutReportZoneLegacy (this entity)  

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

### <a href=#ConfigurationLayoutId name="ConfigurationLayoutId">ConfigurationLayoutId</a>

First included in: Miscellaneous/RetailTillLayoutReportZoneLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfigurationLayoutId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MasterZoneReference name="MasterZoneReference">MasterZoneReference</a>

First included in: Miscellaneous/RetailTillLayoutReportZoneLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MasterZoneReference attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_RetailTillLayoutRelationshipId name="Relationship_RetailTillLayoutRelationshipId">Relationship_RetailTillLayoutRelationshipId</a>

First included in: Miscellaneous/RetailTillLayoutReportZoneLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTillLayoutRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/RetailTillLayoutLegacy.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Parameter/RetailTillLayoutLegacy.cdm.json/RetailTillLayoutLegacy</a></td><td><a href="../Parameter/RetailTillLayoutLegacy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTillLayoutZoneRelationshipId name="Relationship_RetailTillLayoutZoneRelationshipId">Relationship_RetailTillLayoutZoneRelationshipId</a>

First included in: Miscellaneous/RetailTillLayoutReportZoneLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTillLayoutZoneRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailTillLayoutZone.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailTillLayoutZone.cdm.json/RetailTillLayoutZone</a></td><td><a href="RetailTillLayoutZone.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTillLayoutSizeRelationshipId name="Relationship_RetailTillLayoutSizeRelationshipId">Relationship_RetailTillLayoutSizeRelationshipId</a>

First included in: Miscellaneous/RetailTillLayoutReportZoneLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTillLayoutSizeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailTillLayoutSize.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailTillLayoutSize.cdm.json/RetailTillLayoutSize</a></td><td><a href="RetailTillLayoutSize.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTillLayoutZoneReferenceRelationshipId name="Relationship_RetailTillLayoutZoneReferenceRelationshipId">Relationship_RetailTillLayoutZoneReferenceRelationshipId</a>

First included in: Miscellaneous/RetailTillLayoutReportZoneLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTillLayoutZoneReferenceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailTillLayoutZoneReference.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailTillLayoutZoneReference.cdm.json/RetailTillLayoutZoneReference</a></td><td><a href="RetailTillLayoutZoneReference.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Report name="Report">Report</a>

First included in: Miscellaneous/RetailTillLayoutReportZoneLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Report attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>
