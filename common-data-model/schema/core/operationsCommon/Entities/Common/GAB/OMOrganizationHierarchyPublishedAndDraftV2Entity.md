---
title: OMOrganizationHierarchyPublishedAndDraftV2Entity in GAB - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Organization hierarchy V2 - published and draft in GAB(OMOrganizationHierarchyPublishedAndDraftV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Common/GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Organization hierarchy V2 - published and draft</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ChildOrganization](#ChildOrganization)||<a href="OMOrganizationHierarchyPublishedAndDraftV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity</a>|
|[Hierarchy](#Hierarchy)||<a href="OMOrganizationHierarchyPublishedAndDraftV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity</a>|
|[ParentOrganization](#ParentOrganization)||<a href="OMOrganizationHierarchyPublishedAndDraftV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity</a>|
|[ValidFrom](#ValidFrom)||<a href="OMOrganizationHierarchyPublishedAndDraftV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity</a>|
|[ValidTo](#ValidTo)||<a href="OMOrganizationHierarchyPublishedAndDraftV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity</a>|
|[HierarchyType](#HierarchyType)||<a href="OMOrganizationHierarchyPublishedAndDraftV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity</a>|
|[ChildOrganizationName](#ChildOrganizationName)||<a href="OMOrganizationHierarchyPublishedAndDraftV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity</a>|
|[ChildOrganizationPartyNumber](#ChildOrganizationPartyNumber)||<a href="OMOrganizationHierarchyPublishedAndDraftV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity</a>|
|[ParentOrganizationName](#ParentOrganizationName)||<a href="OMOrganizationHierarchyPublishedAndDraftV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity</a>|
|[ParentOrganizationPartyNumber](#ParentOrganizationPartyNumber)||<a href="OMOrganizationHierarchyPublishedAndDraftV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity</a>|
|[RelationshipType](#RelationshipType)||<a href="OMOrganizationHierarchyPublishedAndDraftV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity</a>|
|[IsDraft](#IsDraft)||<a href="OMOrganizationHierarchyPublishedAndDraftV2Entity.md" target="_blank">GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity</a>|

### <a href=#ChildOrganization name="ChildOrganization">ChildOrganization</a>

First included in: GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity (this entity)  

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

First included in: GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity (this entity)  

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

First included in: GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity (this entity)  

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

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity (this entity)  

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

First included in: GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity (this entity)  

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

### <a href=#HierarchyType name="HierarchyType">HierarchyType</a>

First included in: GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChildOrganizationName name="ChildOrganizationName">ChildOrganizationName</a>

First included in: GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChildOrganizationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChildOrganizationPartyNumber name="ChildOrganizationPartyNumber">ChildOrganizationPartyNumber</a>

First included in: GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity (this entity)  

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

First included in: GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity (this entity)  

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

First included in: GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity (this entity)  

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

First included in: GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity (this entity)  

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

### <a href=#IsDraft name="IsDraft">IsDraft</a>

First included in: GAB/OMOrganizationHierarchyPublishedAndDraftV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDraft attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
