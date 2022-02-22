---
title: OMOrganizationHierarchyV2Entity in GAB - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Organization hierarchy V2 in GAB(OMOrganizationHierarchyV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Common/GAB/OMOrganizationHierarchyV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Organization hierarchy V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ChildOrganization](#ChildOrganization)||<a href="OMOrganizationHierarchyV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyV2Entity</a>|
|[Hierarchy](#Hierarchy)||<a href="OMOrganizationHierarchyV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyV2Entity</a>|
|[ParentOrganization](#ParentOrganization)||<a href="OMOrganizationHierarchyV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyV2Entity</a>|
|[validFrom](#validFrom)||<a href="OMOrganizationHierarchyV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyV2Entity</a>|
|[validTo](#validTo)||<a href="OMOrganizationHierarchyV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyV2Entity</a>|
|[HierarchyType](#HierarchyType)||<a href="OMOrganizationHierarchyV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyV2Entity</a>|
|[ChildOrganizationName](#ChildOrganizationName)||<a href="OMOrganizationHierarchyV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyV2Entity</a>|
|[ChildOrganizationPartyNumber](#ChildOrganizationPartyNumber)||<a href="OMOrganizationHierarchyV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyV2Entity</a>|
|[ParentOrganizationName](#ParentOrganizationName)||<a href="OMOrganizationHierarchyV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyV2Entity</a>|
|[ParentOrganizationPartyNumber](#ParentOrganizationPartyNumber)||<a href="OMOrganizationHierarchyV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyV2Entity</a>|
|[RelationshipType](#RelationshipType)||<a href="OMOrganizationHierarchyV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyV2Entity</a>|
|[BackingTable_OMRevisionEditRelationshipId](#BackingTable_OMRevisionEditRelationshipId)||<a href="OMOrganizationHierarchyV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyV2Entity</a>|

### <a href=#ChildOrganization name="ChildOrganization">ChildOrganization</a>

First included in: GAB/OMOrganizationHierarchyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChildOrganization attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Hierarchy name="Hierarchy">Hierarchy</a>

First included in: GAB/OMOrganizationHierarchyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Hierarchy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentOrganization name="ParentOrganization">ParentOrganization</a>

First included in: GAB/OMOrganizationHierarchyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentOrganization attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#validFrom name="validFrom">validFrom</a>

First included in: GAB/OMOrganizationHierarchyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the validFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#validTo name="validTo">validTo</a>

First included in: GAB/OMOrganizationHierarchyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the validTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyType name="HierarchyType">HierarchyType</a>

First included in: GAB/OMOrganizationHierarchyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChildOrganizationName name="ChildOrganizationName">ChildOrganizationName</a>

First included in: GAB/OMOrganizationHierarchyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChildOrganizationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChildOrganizationPartyNumber name="ChildOrganizationPartyNumber">ChildOrganizationPartyNumber</a>

First included in: GAB/OMOrganizationHierarchyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChildOrganizationPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentOrganizationName name="ParentOrganizationName">ParentOrganizationName</a>

First included in: GAB/OMOrganizationHierarchyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentOrganizationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentOrganizationPartyNumber name="ParentOrganizationPartyNumber">ParentOrganizationPartyNumber</a>

First included in: GAB/OMOrganizationHierarchyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentOrganizationPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RelationshipType name="RelationshipType">RelationshipType</a>

First included in: GAB/OMOrganizationHierarchyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RelationshipType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_OMRevisionEditRelationshipId name="BackingTable_OMRevisionEditRelationshipId">BackingTable_OMRevisionEditRelationshipId</a>

First included in: GAB/OMOrganizationHierarchyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_OMRevisionEditRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Common/GAB/Main/OMRevisionEdit.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/OMRevisionEdit.cdm.json/OMRevisionEdit</a></td><td><a href="../../../Tables/Common/GAB/Main/OMRevisionEdit.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
