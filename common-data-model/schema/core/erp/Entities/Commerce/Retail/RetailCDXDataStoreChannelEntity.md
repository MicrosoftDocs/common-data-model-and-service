---
title: RetailCDXDataStoreChannelEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailCDXDataStoreChannelEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailCDXDataStoreChannelEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[ChannelId](#ChannelId)||<a href="RetailCDXDataStoreChannelEntity.md" target="_blank">Retail/RetailCDXDataStoreChannelEntity</a>|
|[ChannelDatabaseId](#ChannelDatabaseId)||<a href="RetailCDXDataStoreChannelEntity.md" target="_blank">Retail/RetailCDXDataStoreChannelEntity</a>|
|[BackingTable_RetailCDXDataStoreChannelRelationshipId](#BackingTable_RetailCDXDataStoreChannelRelationshipId)||<a href="RetailCDXDataStoreChannelEntity.md" target="_blank">Retail/RetailCDXDataStoreChannelEntity</a>|

### <a href=#ChannelId name="ChannelId">ChannelId</a>

First included in: Retail/RetailCDXDataStoreChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChannelDatabaseId name="ChannelDatabaseId">ChannelDatabaseId</a>

First included in: Retail/RetailCDXDataStoreChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelDatabaseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailCDXDataStoreChannelRelationshipId name="BackingTable_RetailCDXDataStoreChannelRelationshipId">BackingTable_RetailCDXDataStoreChannelRelationshipId</a>

First included in: Retail/RetailCDXDataStoreChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailCDXDataStoreChannelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/Retail/Main/RetailCDXDataStoreChannel.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailCDXDataStoreChannel.cdm.json/RetailCDXDataStoreChannel</a></td><td><a href="../../../Tables/Commerce/Retail/Main/RetailCDXDataStoreChannel.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
