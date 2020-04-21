---
title: LedgerRRGEDocumentVersions_W - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# LedgerRRGEDocumentVersions_W

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/Miscellaneous/LedgerRRGEDocumentVersions_W.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerRRGEDocumentVersions_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerRRGEDocumentVersions_W.md" target="_blank">Miscellaneous/LedgerRRGEDocumentVersions_W</a>|
|[BaseDate](#BaseDate)||<a href="LedgerRRGEDocumentVersions_W.md" target="_blank">Miscellaneous/LedgerRRGEDocumentVersions_W</a>|
|[File](#File)||<a href="LedgerRRGEDocumentVersions_W.md" target="_blank">Miscellaneous/LedgerRRGEDocumentVersions_W</a>|
|[FileName](#FileName)||<a href="LedgerRRGEDocumentVersions_W.md" target="_blank">Miscellaneous/LedgerRRGEDocumentVersions_W</a>|
|[LedgerRRGEDocuments_W](#LedgerRRGEDocuments_W)||<a href="LedgerRRGEDocumentVersions_W.md" target="_blank">Miscellaneous/LedgerRRGEDocumentVersions_W</a>|
|[LedgerRRGETemplates_W](#LedgerRRGETemplates_W)||<a href="LedgerRRGEDocumentVersions_W.md" target="_blank">Miscellaneous/LedgerRRGEDocumentVersions_W</a>|
|[Notes](#Notes)||<a href="LedgerRRGEDocumentVersions_W.md" target="_blank">Miscellaneous/LedgerRRGEDocumentVersions_W</a>|
|[ParentRefRecId](#ParentRefRecId)||<a href="LedgerRRGEDocumentVersions_W.md" target="_blank">Miscellaneous/LedgerRRGEDocumentVersions_W</a>|
|[SessionId](#SessionId)||<a href="LedgerRRGEDocumentVersions_W.md" target="_blank">Miscellaneous/LedgerRRGEDocumentVersions_W</a>|
|[SessionLoginDateTime](#SessionLoginDateTime)||<a href="LedgerRRGEDocumentVersions_W.md" target="_blank">Miscellaneous/LedgerRRGEDocumentVersions_W</a>|
|[Type](#Type)||<a href="LedgerRRGEDocumentVersions_W.md" target="_blank">Miscellaneous/LedgerRRGEDocumentVersions_W</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerRRGEDocumentVersions_W.md" target="_blank">Miscellaneous/LedgerRRGEDocumentVersions_W</a>|
|[Relationship_LedgerRRGEDocuments_WRelationshipId](#Relationship_LedgerRRGEDocuments_WRelationshipId)||<a href="LedgerRRGEDocumentVersions_W.md" target="_blank">Miscellaneous/LedgerRRGEDocumentVersions_W</a>|
|[Relationship_LedgerRRGETemplates_WRelationshipId](#Relationship_LedgerRRGETemplates_WRelationshipId)||<a href="LedgerRRGEDocumentVersions_W.md" target="_blank">Miscellaneous/LedgerRRGEDocumentVersions_W</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerRRGEDocumentVersions_W.md" target="_blank">Miscellaneous/LedgerRRGEDocumentVersions_W</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/LedgerRRGEDocumentVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerRRGEDocumentVersions_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BaseDate name="BaseDate">BaseDate</a>

First included in: Miscellaneous/LedgerRRGEDocumentVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#File name="File">File</a>

First included in: Miscellaneous/LedgerRRGEDocumentVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the File attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#FileName name="FileName">FileName</a>

First included in: Miscellaneous/LedgerRRGEDocumentVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerRRGEDocuments_W name="LedgerRRGEDocuments_W">LedgerRRGEDocuments_W</a>

First included in: Miscellaneous/LedgerRRGEDocumentVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerRRGEDocuments_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerRRGETemplates_W name="LedgerRRGETemplates_W">LedgerRRGETemplates_W</a>

First included in: Miscellaneous/LedgerRRGEDocumentVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerRRGETemplates_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Notes name="Notes">Notes</a>

First included in: Miscellaneous/LedgerRRGEDocumentVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Notes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentRefRecId name="ParentRefRecId">ParentRefRecId</a>

First included in: Miscellaneous/LedgerRRGEDocumentVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SessionId name="SessionId">SessionId</a>

First included in: Miscellaneous/LedgerRRGEDocumentVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SessionLoginDateTime name="SessionLoginDateTime">SessionLoginDateTime</a>

First included in: Miscellaneous/LedgerRRGEDocumentVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionLoginDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Type name="Type">Type</a>

First included in: Miscellaneous/LedgerRRGEDocumentVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Type attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/LedgerRRGEDocumentVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerRRGEDocuments_WRelationshipId name="Relationship_LedgerRRGEDocuments_WRelationshipId">Relationship_LedgerRRGEDocuments_WRelationshipId</a>

First included in: Miscellaneous/LedgerRRGEDocumentVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRRGEDocuments_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/LedgerRRGEDocuments_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/LedgerRRGEDocuments_W.cdm.json/LedgerRRGEDocuments_W</a></td><td><a href="../Main/LedgerRRGEDocuments_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerRRGETemplates_WRelationshipId name="Relationship_LedgerRRGETemplates_WRelationshipId">Relationship_LedgerRRGETemplates_WRelationshipId</a>

First included in: Miscellaneous/LedgerRRGEDocumentVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRRGETemplates_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/LedgerRRGETemplates_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Group/LedgerRRGETemplates_W.cdm.json/LedgerRRGETemplates_W</a></td><td><a href="../Group/LedgerRRGETemplates_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/LedgerRRGEDocumentVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
