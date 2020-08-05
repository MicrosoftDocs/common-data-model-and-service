---
title: RetailWarrantyApplicableChannelEntity in Merchandising - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Applicable channels in Merchandising(RetailWarrantyApplicableChannelEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/Merchandising/RetailWarrantyApplicableChannelEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Applicable channels</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WarrantyGroupId](#WarrantyGroupId)||<a href="RetailWarrantyApplicableChannelEntity.md" target="_blank">Merchandising/RetailWarrantyApplicableChannelEntity</a>|
|[OMHierarchyTypeId](#OMHierarchyTypeId)||<a href="RetailWarrantyApplicableChannelEntity.md" target="_blank">Merchandising/RetailWarrantyApplicableChannelEntity</a>|
|[OMInternalOrganizationId](#OMInternalOrganizationId)||<a href="RetailWarrantyApplicableChannelEntity.md" target="_blank">Merchandising/RetailWarrantyApplicableChannelEntity</a>|
|[WarrantyGroupName](#WarrantyGroupName)||<a href="RetailWarrantyApplicableChannelEntity.md" target="_blank">Merchandising/RetailWarrantyApplicableChannelEntity</a>|
|[OMHierarchyType](#OMHierarchyType)||<a href="RetailWarrantyApplicableChannelEntity.md" target="_blank">Merchandising/RetailWarrantyApplicableChannelEntity</a>|
|[ChannelName](#ChannelName)||<a href="RetailWarrantyApplicableChannelEntity.md" target="_blank">Merchandising/RetailWarrantyApplicableChannelEntity</a>|
|[PartyNumber](#PartyNumber)||<a href="RetailWarrantyApplicableChannelEntity.md" target="_blank">Merchandising/RetailWarrantyApplicableChannelEntity</a>|
|[Status](#Status)||<a href="RetailWarrantyApplicableChannelEntity.md" target="_blank">Merchandising/RetailWarrantyApplicableChannelEntity</a>|
|[LineIdentifier](#LineIdentifier)||<a href="RetailWarrantyApplicableChannelEntity.md" target="_blank">Merchandising/RetailWarrantyApplicableChannelEntity</a>|
|[BackingTable_RetailWarrantyApplicableChannelRelationshipId](#BackingTable_RetailWarrantyApplicableChannelRelationshipId)||<a href="RetailWarrantyApplicableChannelEntity.md" target="_blank">Merchandising/RetailWarrantyApplicableChannelEntity</a>|

### <a href=#WarrantyGroupId name="WarrantyGroupId">WarrantyGroupId</a>

First included in: Merchandising/RetailWarrantyApplicableChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantyGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMHierarchyTypeId name="OMHierarchyTypeId">OMHierarchyTypeId</a>

First included in: Merchandising/RetailWarrantyApplicableChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMHierarchyTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMInternalOrganizationId name="OMInternalOrganizationId">OMInternalOrganizationId</a>

First included in: Merchandising/RetailWarrantyApplicableChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMInternalOrganizationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarrantyGroupName name="WarrantyGroupName">WarrantyGroupName</a>

First included in: Merchandising/RetailWarrantyApplicableChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarrantyGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMHierarchyType name="OMHierarchyType">OMHierarchyType</a>

First included in: Merchandising/RetailWarrantyApplicableChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMHierarchyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChannelName name="ChannelName">ChannelName</a>

First included in: Merchandising/RetailWarrantyApplicableChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyNumber name="PartyNumber">PartyNumber</a>

First included in: Merchandising/RetailWarrantyApplicableChannelEntity (this entity)  

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

### <a href=#Status name="Status">Status</a>

First included in: Merchandising/RetailWarrantyApplicableChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineIdentifier name="LineIdentifier">LineIdentifier</a>

First included in: Merchandising/RetailWarrantyApplicableChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineIdentifier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailWarrantyApplicableChannelRelationshipId name="BackingTable_RetailWarrantyApplicableChannelRelationshipId">BackingTable_RetailWarrantyApplicableChannelRelationshipId</a>

First included in: Merchandising/RetailWarrantyApplicableChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailWarrantyApplicableChannelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/Merchandising/Group/RetailWarrantyApplicableChannel.md" target="_blank">/core/operationsCommon/Tables/Commerce/Merchandising/Group/RetailWarrantyApplicableChannel.cdm.json/RetailWarrantyApplicableChannel</a></td><td><a href="../../../Tables/Commerce/Merchandising/Group/RetailWarrantyApplicableChannel.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
