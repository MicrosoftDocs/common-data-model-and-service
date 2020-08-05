---
title: RetailStoreLocatorGroupMemberEntity in BrickAndMortarStore - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Retail locator group member in BrickAndMortarStore(RetailStoreLocatorGroupMemberEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/ChannelManagement/BrickAndMortarStore/RetailStoreLocatorGroupMemberEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Retail locator group member</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[LocatorGroup](#LocatorGroup)||<a href="RetailStoreLocatorGroupMemberEntity.md" target="_blank">BrickAndMortarStore/RetailStoreLocatorGroupMemberEntity</a>|
|[Store](#Store)||<a href="RetailStoreLocatorGroupMemberEntity.md" target="_blank">BrickAndMortarStore/RetailStoreLocatorGroupMemberEntity</a>|
|[StoreLocatorGroupName](#StoreLocatorGroupName)||<a href="RetailStoreLocatorGroupMemberEntity.md" target="_blank">BrickAndMortarStore/RetailStoreLocatorGroupMemberEntity</a>|
|[OMOperatingUnitNumber](#OMOperatingUnitNumber)||<a href="RetailStoreLocatorGroupMemberEntity.md" target="_blank">BrickAndMortarStore/RetailStoreLocatorGroupMemberEntity</a>|
|[OMOperatingUnitID](#OMOperatingUnitID)||<a href="RetailStoreLocatorGroupMemberEntity.md" target="_blank">BrickAndMortarStore/RetailStoreLocatorGroupMemberEntity</a>|
|[InventLocationDataAreaId](#InventLocationDataAreaId)||<a href="RetailStoreLocatorGroupMemberEntity.md" target="_blank">BrickAndMortarStore/RetailStoreLocatorGroupMemberEntity</a>|
|[InventLocationId](#InventLocationId)||<a href="RetailStoreLocatorGroupMemberEntity.md" target="_blank">BrickAndMortarStore/RetailStoreLocatorGroupMemberEntity</a>|
|[BackingTable_RetailStoreLocatorGroupMemberRelationshipId](#BackingTable_RetailStoreLocatorGroupMemberRelationshipId)||<a href="RetailStoreLocatorGroupMemberEntity.md" target="_blank">BrickAndMortarStore/RetailStoreLocatorGroupMemberEntity</a>|

### <a href=#LocatorGroup name="LocatorGroup">LocatorGroup</a>

First included in: BrickAndMortarStore/RetailStoreLocatorGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocatorGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Store name="Store">Store</a>

First included in: BrickAndMortarStore/RetailStoreLocatorGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Store</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Store attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Store</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StoreLocatorGroupName name="StoreLocatorGroupName">StoreLocatorGroupName</a>

First included in: BrickAndMortarStore/RetailStoreLocatorGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreLocatorGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMOperatingUnitNumber name="OMOperatingUnitNumber">OMOperatingUnitNumber</a>

First included in: BrickAndMortarStore/RetailStoreLocatorGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMOperatingUnitNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMOperatingUnitID name="OMOperatingUnitID">OMOperatingUnitID</a>

First included in: BrickAndMortarStore/RetailStoreLocatorGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMOperatingUnitID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocationDataAreaId name="InventLocationDataAreaId">InventLocationDataAreaId</a>

First included in: BrickAndMortarStore/RetailStoreLocatorGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocationId name="InventLocationId">InventLocationId</a>

First included in: BrickAndMortarStore/RetailStoreLocatorGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailStoreLocatorGroupMemberRelationshipId name="BackingTable_RetailStoreLocatorGroupMemberRelationshipId">BackingTable_RetailStoreLocatorGroupMemberRelationshipId</a>

First included in: BrickAndMortarStore/RetailStoreLocatorGroupMemberEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailStoreLocatorGroupMemberRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailStoreLocatorGroupMember.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailStoreLocatorGroupMember.cdm.json/RetailStoreLocatorGroupMember</a></td><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailStoreLocatorGroupMember.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
