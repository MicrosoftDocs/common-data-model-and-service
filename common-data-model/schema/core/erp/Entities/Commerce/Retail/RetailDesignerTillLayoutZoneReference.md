---
title: RetailDesignerTillLayoutZoneReference - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailDesignerTillLayoutZoneReference

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailDesignerTillLayoutZoneReference.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[InstanceRelationType](#InstanceRelationType)||<a href="RetailDesignerTillLayoutZoneReference.md" target="_blank">Retail/RetailDesignerTillLayoutZoneReference</a>|
|[LayoutId](#LayoutId)||<a href="RetailDesignerTillLayoutZoneReference.md" target="_blank">Retail/RetailDesignerTillLayoutZoneReference</a>|
|[Zone](#Zone)||<a href="RetailDesignerTillLayoutZoneReference.md" target="_blank">Retail/RetailDesignerTillLayoutZoneReference</a>|
|[AxRecId](#AxRecId)||<a href="RetailDesignerTillLayoutZoneReference.md" target="_blank">Retail/RetailDesignerTillLayoutZoneReference</a>|
|[BackingTable_RetailTillLayoutZoneReferenceRelationshipId](#BackingTable_RetailTillLayoutZoneReferenceRelationshipId)||<a href="RetailDesignerTillLayoutZoneReference.md" target="_blank">Retail/RetailDesignerTillLayoutZoneReference</a>|

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Retail/RetailDesignerTillLayoutZoneReference (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LayoutId name="LayoutId">LayoutId</a>

First included in: Retail/RetailDesignerTillLayoutZoneReference (this entity)  

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

First included in: Retail/RetailDesignerTillLayoutZoneReference (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Zone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AxRecId name="AxRecId">AxRecId</a>

First included in: Retail/RetailDesignerTillLayoutZoneReference (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AxRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailTillLayoutZoneReferenceRelationshipId name="BackingTable_RetailTillLayoutZoneReferenceRelationshipId">BackingTable_RetailTillLayoutZoneReferenceRelationshipId</a>

First included in: Retail/RetailDesignerTillLayoutZoneReference (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTillLayoutZoneReferenceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/Retail/Miscellaneous/RetailTillLayoutZoneReference.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailTillLayoutZoneReference.cdm.json/RetailTillLayoutZoneReference</a></td><td><a href="../../../Tables/Commerce/Retail/Miscellaneous/RetailTillLayoutZoneReference.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
