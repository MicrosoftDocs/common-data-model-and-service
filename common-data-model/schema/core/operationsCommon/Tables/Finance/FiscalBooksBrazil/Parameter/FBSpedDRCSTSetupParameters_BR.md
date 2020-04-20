---
title: FBSpedDRCSTSetupParameters_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# FBSpedDRCSTSetupParameters_BR

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Parameter/FBSpedDRCSTSetupParameters_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBSpedDRCSTSetupParameters_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBSpedDRCSTSetupParameters_BR.md" target="_blank">Parameter/FBSpedDRCSTSetupParameters_BR</a>|
|[ActivityType](#ActivityType)||<a href="FBSpedDRCSTSetupParameters_BR.md" target="_blank">Parameter/FBSpedDRCSTSetupParameters_BR</a>|
|[FiscalEstablishmentDataArea](#FiscalEstablishmentDataArea)||<a href="FBSpedDRCSTSetupParameters_BR.md" target="_blank">Parameter/FBSpedDRCSTSetupParameters_BR</a>|
|[FiscalEstablishmentId](#FiscalEstablishmentId)||<a href="FBSpedDRCSTSetupParameters_BR.md" target="_blank">Parameter/FBSpedDRCSTSetupParameters_BR</a>|
|[Profile](#Profile)||<a href="FBSpedDRCSTSetupParameters_BR.md" target="_blank">Parameter/FBSpedDRCSTSetupParameters_BR</a>|
|[Version](#Version)||<a href="FBSpedDRCSTSetupParameters_BR.md" target="_blank">Parameter/FBSpedDRCSTSetupParameters_BR</a>|
|[URL](#URL)||<a href="FBSpedDRCSTSetupParameters_BR.md" target="_blank">Parameter/FBSpedDRCSTSetupParameters_BR</a>|
|[RequestHeader](#RequestHeader)||<a href="FBSpedDRCSTSetupParameters_BR.md" target="_blank">Parameter/FBSpedDRCSTSetupParameters_BR</a>|
|[Relationship_FiscalEstablishmentRelationshipId](#Relationship_FiscalEstablishmentRelationshipId)||<a href="FBSpedDRCSTSetupParameters_BR.md" target="_blank">Parameter/FBSpedDRCSTSetupParameters_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/FBSpedDRCSTSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBSpedDRCSTSetupParameters_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ActivityType name="ActivityType">ActivityType</a>

First included in: Parameter/FBSpedDRCSTSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FiscalEstablishmentDataArea name="FiscalEstablishmentDataArea">FiscalEstablishmentDataArea</a>

First included in: Parameter/FBSpedDRCSTSetupParameters_BR (this entity)  

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

First included in: Parameter/FBSpedDRCSTSetupParameters_BR (this entity)  

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

### <a href=#Profile name="Profile">Profile</a>

First included in: Parameter/FBSpedDRCSTSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Profile attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Version name="Version">Version</a>

First included in: Parameter/FBSpedDRCSTSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Version attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#URL name="URL">URL</a>

First included in: Parameter/FBSpedDRCSTSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the URL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestHeader name="RequestHeader">RequestHeader</a>

First included in: Parameter/FBSpedDRCSTSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestHeader attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalEstablishmentRelationshipId name="Relationship_FiscalEstablishmentRelationshipId">Relationship_FiscalEstablishmentRelationshipId</a>

First included in: Parameter/FBSpedDRCSTSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalEstablishmentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FiscalEstablishment_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FiscalEstablishment_BR.cdm.json/FiscalEstablishment_BR</a></td><td><a href="../Main/FiscalEstablishment_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
