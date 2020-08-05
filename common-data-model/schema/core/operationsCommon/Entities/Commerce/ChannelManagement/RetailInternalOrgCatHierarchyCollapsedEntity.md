---
title: RetailInternalOrgCatHierarchyCollapsedEntity in ChannelManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Navigation Hierarchy in ChannelManagement(RetailInternalOrgCatHierarchyCollapsedEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Navigation Hierarchy</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AncestorInternalOrg](#AncestorInternalOrg)||<a href="RetailInternalOrgCatHierarchyCollapsedEntity.md" target="_blank">ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity</a>|
|[CategoryHierarchy](#CategoryHierarchy)||<a href="RetailInternalOrgCatHierarchyCollapsedEntity.md" target="_blank">ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity</a>|
|[Distance](#Distance)||<a href="RetailInternalOrgCatHierarchyCollapsedEntity.md" target="_blank">ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity</a>|
|[Origin](#Origin)||<a href="RetailInternalOrgCatHierarchyCollapsedEntity.md" target="_blank">ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity</a>|
|[OriginRecVersion](#OriginRecVersion)||<a href="RetailInternalOrgCatHierarchyCollapsedEntity.md" target="_blank">ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity</a>|
|[ValidFrom](#ValidFrom)||<a href="RetailInternalOrgCatHierarchyCollapsedEntity.md" target="_blank">ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity</a>|
|[ValidTo](#ValidTo)||<a href="RetailInternalOrgCatHierarchyCollapsedEntity.md" target="_blank">ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity</a>|
|[PartyNumber](#PartyNumber)||<a href="RetailInternalOrgCatHierarchyCollapsedEntity.md" target="_blank">ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity</a>|
|[Relationship_RetailStoreEntityRelationshipId](#Relationship_RetailStoreEntityRelationshipId)||<a href="RetailInternalOrgCatHierarchyCollapsedEntity.md" target="_blank">ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity</a>|
|[Relationship_RetailOnlineChannelEntityRelationshipId](#Relationship_RetailOnlineChannelEntityRelationshipId)||<a href="RetailInternalOrgCatHierarchyCollapsedEntity.md" target="_blank">ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity</a>|
|[Relationship_RetailCallCenterEntityRelationshipId](#Relationship_RetailCallCenterEntityRelationshipId)||<a href="RetailInternalOrgCatHierarchyCollapsedEntity.md" target="_blank">ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity</a>|

### <a href=#AncestorInternalOrg name="AncestorInternalOrg">AncestorInternalOrg</a>

First included in: ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AncestorInternalOrg attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryHierarchy name="CategoryHierarchy">CategoryHierarchy</a>

First included in: ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryHierarchy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Distance name="Distance">Distance</a>

First included in: ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Distance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Origin name="Origin">Origin</a>

First included in: ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Origin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginRecVersion name="OriginRecVersion">OriginRecVersion</a>

First included in: ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginRecVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyNumber name="PartyNumber">PartyNumber</a>

First included in: ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStoreEntityRelationshipId name="Relationship_RetailStoreEntityRelationshipId">Relationship_RetailStoreEntityRelationshipId</a>

First included in: ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStoreEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailOnlineChannelEntityRelationshipId name="Relationship_RetailOnlineChannelEntityRelationshipId">Relationship_RetailOnlineChannelEntityRelationshipId</a>

First included in: ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailOnlineChannelEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailCallCenterEntityRelationshipId name="Relationship_RetailCallCenterEntityRelationshipId">Relationship_RetailCallCenterEntityRelationshipId</a>

First included in: ChannelManagement/RetailInternalOrgCatHierarchyCollapsedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailCallCenterEntityRelationshipId attribute are listed below.</summary>

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
