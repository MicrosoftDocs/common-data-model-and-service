---
title: RetailAttributeMetadataEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# @RET261216

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailAttributeMetadataEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@RET261216</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Entity|
|---|---|---|
|[TypeName](#TypeName)||<a href="RetailAttributeMetadataEntity.md" target="_blank">Retail/RetailAttributeMetadataEntity</a>|
|[AttributeName](#AttributeName)||<a href="RetailAttributeMetadataEntity.md" target="_blank">Retail/RetailAttributeMetadataEntity</a>|
|[XmlMetadata](#XmlMetadata)||<a href="RetailAttributeMetadataEntity.md" target="_blank">Retail/RetailAttributeMetadataEntity</a>|
|[XmlMetadataVersionNumber](#XmlMetadataVersionNumber)||<a href="RetailAttributeMetadataEntity.md" target="_blank">Retail/RetailAttributeMetadataEntity</a>|
|[Relationship_AttributeMasterRelationshipId](#Relationship_AttributeMasterRelationshipId)||<a href="RetailAttributeMetadataEntity.md" target="_blank">Retail/RetailAttributeMetadataEntity</a>|
|[BackingTable_RetailAttributeMetadataRelationshipId](#BackingTable_RetailAttributeMetadataRelationshipId)||<a href="RetailAttributeMetadataEntity.md" target="_blank">Retail/RetailAttributeMetadataEntity</a>|

### <a href=#TypeName name="TypeName">TypeName</a>

First included in: Retail/RetailAttributeMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttributeName name="AttributeName">AttributeName</a>

First included in: Retail/RetailAttributeMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#XmlMetadata name="XmlMetadata">XmlMetadata</a>

First included in: Retail/RetailAttributeMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XmlMetadata attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#XmlMetadataVersionNumber name="XmlMetadataVersionNumber">XmlMetadataVersionNumber</a>

First included in: Retail/RetailAttributeMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XmlMetadataVersionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AttributeMasterRelationshipId name="Relationship_AttributeMasterRelationshipId">Relationship_AttributeMasterRelationshipId</a>

First included in: Retail/RetailAttributeMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AttributeMasterRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_RetailAttributeMetadataRelationshipId name="BackingTable_RetailAttributeMetadataRelationshipId">BackingTable_RetailAttributeMetadataRelationshipId</a>

First included in: Retail/RetailAttributeMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailAttributeMetadataRelationshipId attribute are listed below.</summary>

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
