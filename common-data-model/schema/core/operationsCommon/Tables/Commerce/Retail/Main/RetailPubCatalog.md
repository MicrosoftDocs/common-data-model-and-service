---
title: RetailPubCatalog - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailPubCatalog

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Main/RetailPubCatalog.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailPubCatalog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailPubCatalog.md" target="_blank">Main/RetailPubCatalog</a>|
|[EnableSnapshot](#EnableSnapshot)||<a href="RetailPubCatalog.md" target="_blank">Main/RetailPubCatalog</a>|
|[Origin](#Origin)||<a href="RetailPubCatalog.md" target="_blank">Main/RetailPubCatalog</a>|
|[OriginRecVersion](#OriginRecVersion)||<a href="RetailPubCatalog.md" target="_blank">Main/RetailPubCatalog</a>|
|[Owner](#Owner)||<a href="RetailPubCatalog.md" target="_blank">Main/RetailPubCatalog</a>|
|[PublishedDateTime](#PublishedDateTime)||<a href="RetailPubCatalog.md" target="_blank">Main/RetailPubCatalog</a>|
|[PublishedValidFrom](#PublishedValidFrom)||<a href="RetailPubCatalog.md" target="_blank">Main/RetailPubCatalog</a>|
|[PublishedValidTo](#PublishedValidTo)||<a href="RetailPubCatalog.md" target="_blank">Main/RetailPubCatalog</a>|
|[State](#State)||<a href="RetailPubCatalog.md" target="_blank">Main/RetailPubCatalog</a>|
|[ValidFrom](#ValidFrom)||<a href="RetailPubCatalog.md" target="_blank">Main/RetailPubCatalog</a>|
|[ValidFromDateTime](#ValidFromDateTime)||<a href="RetailPubCatalog.md" target="_blank">Main/RetailPubCatalog</a>|
|[ValidTo](#ValidTo)||<a href="RetailPubCatalog.md" target="_blank">Main/RetailPubCatalog</a>|
|[LegacyModifiedBy](#LegacyModifiedBy)||<a href="RetailPubCatalog.md" target="_blank">Main/RetailPubCatalog</a>|
|[Relationship_DirPersonRelationshipId](#Relationship_DirPersonRelationshipId)||<a href="RetailPubCatalog.md" target="_blank">Main/RetailPubCatalog</a>|
|[Relationship_OriginRelationshipId](#Relationship_OriginRelationshipId)||<a href="RetailPubCatalog.md" target="_blank">Main/RetailPubCatalog</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/RetailPubCatalog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailPubCatalog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EnableSnapshot name="EnableSnapshot">EnableSnapshot</a>

First included in: Main/RetailPubCatalog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableSnapshot attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Origin name="Origin">Origin</a>

First included in: Main/RetailPubCatalog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Origin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OriginRecVersion name="OriginRecVersion">OriginRecVersion</a>

First included in: Main/RetailPubCatalog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginRecVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Owner name="Owner">Owner</a>

First included in: Main/RetailPubCatalog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Owner attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PublishedDateTime name="PublishedDateTime">PublishedDateTime</a>

First included in: Main/RetailPubCatalog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PublishedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PublishedValidFrom name="PublishedValidFrom">PublishedValidFrom</a>

First included in: Main/RetailPubCatalog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PublishedValidFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PublishedValidTo name="PublishedValidTo">PublishedValidTo</a>

First included in: Main/RetailPubCatalog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PublishedValidTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#State name="State">State</a>

First included in: Main/RetailPubCatalog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the State attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: Main/RetailPubCatalog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ValidFromDateTime name="ValidFromDateTime">ValidFromDateTime</a>

First included in: Main/RetailPubCatalog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFromDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: Main/RetailPubCatalog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#LegacyModifiedBy name="LegacyModifiedBy">LegacyModifiedBy</a>

First included in: Main/RetailPubCatalog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegacyModifiedBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DirPersonRelationshipId name="Relationship_DirPersonRelationshipId">Relationship_DirPersonRelationshipId</a>

First included in: Main/RetailPubCatalog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DirPersonRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/DirPerson.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/DirPerson.cdm.json/DirPerson</a></td><td><a href="../../../Common/GAB/Main/DirPerson.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OriginRelationshipId name="Relationship_OriginRelationshipId">Relationship_OriginRelationshipId</a>

First included in: Main/RetailPubCatalog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OriginRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="Catalog.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/Catalog.cdm.json/Catalog</a></td><td><a href="Catalog.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
