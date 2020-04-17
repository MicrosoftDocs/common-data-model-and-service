---
title: FBSpedFiscal4218SPFileParameters_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# FBSpedFiscal4218SPFileParameters_BR

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/FiscalBooksBrazil/Parameter/FBSpedFiscal4218SPFileParameters_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBSpedFiscal4218SPFileParameters_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBSpedFiscal4218SPFileParameters_BR.md" target="_blank">Parameter/FBSpedFiscal4218SPFileParameters_BR</a>|
|[FBSpedFiscal4218FileType](#FBSpedFiscal4218FileType)||<a href="FBSpedFiscal4218SPFileParameters_BR.md" target="_blank">Parameter/FBSpedFiscal4218SPFileParameters_BR</a>|
|[FileLocation](#FileLocation)||<a href="FBSpedFiscal4218SPFileParameters_BR.md" target="_blank">Parameter/FBSpedFiscal4218SPFileParameters_BR</a>|
|[FiscalEstablishmentDataArea](#FiscalEstablishmentDataArea)||<a href="FBSpedFiscal4218SPFileParameters_BR.md" target="_blank">Parameter/FBSpedFiscal4218SPFileParameters_BR</a>|
|[FiscalEstablishmentId](#FiscalEstablishmentId)||<a href="FBSpedFiscal4218SPFileParameters_BR.md" target="_blank">Parameter/FBSpedFiscal4218SPFileParameters_BR</a>|
|[Version](#Version)||<a href="FBSpedFiscal4218SPFileParameters_BR.md" target="_blank">Parameter/FBSpedFiscal4218SPFileParameters_BR</a>|
|[Relationship_FiscalEstablishment_BRRelationshipId](#Relationship_FiscalEstablishment_BRRelationshipId)||<a href="FBSpedFiscal4218SPFileParameters_BR.md" target="_blank">Parameter/FBSpedFiscal4218SPFileParameters_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/FBSpedFiscal4218SPFileParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBSpedFiscal4218SPFileParameters_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FBSpedFiscal4218FileType name="FBSpedFiscal4218FileType">FBSpedFiscal4218FileType</a>

First included in: Parameter/FBSpedFiscal4218SPFileParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBSpedFiscal4218FileType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FileLocation name="FileLocation">FileLocation</a>

First included in: Parameter/FBSpedFiscal4218SPFileParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentDataArea name="FiscalEstablishmentDataArea">FiscalEstablishmentDataArea</a>

First included in: Parameter/FBSpedFiscal4218SPFileParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalEstablishmentId name="FiscalEstablishmentId">FiscalEstablishmentId</a>

First included in: Parameter/FBSpedFiscal4218SPFileParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalEstablishmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Version name="Version">Version</a>

First included in: Parameter/FBSpedFiscal4218SPFileParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Version attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_FiscalEstablishment_BRRelationshipId name="Relationship_FiscalEstablishment_BRRelationshipId">Relationship_FiscalEstablishment_BRRelationshipId</a>

First included in: Parameter/FBSpedFiscal4218SPFileParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalEstablishment_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FiscalEstablishment_BR.md" target="_blank">/core/erp/Tables/Finance/FiscalBooksBrazil/Main/FiscalEstablishment_BR.cdm.json/FiscalEstablishment_BR</a></td><td><a href="../Main/FiscalEstablishment_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
