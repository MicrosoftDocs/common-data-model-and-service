---
title: DemoDataPostRunDocument - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# DemoDataPostRunDocument

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsPayable/Miscellaneous/DemoDataPostRunDocument.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DemoDataPostRunDocument/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="DemoDataPostRunDocument.md" target="_blank">Miscellaneous/DemoDataPostRunDocument</a>|
|[RunId](#RunId)||<a href="DemoDataPostRunDocument.md" target="_blank">Miscellaneous/DemoDataPostRunDocument</a>|
|[LineNum](#LineNum)||<a href="DemoDataPostRunDocument.md" target="_blank">Miscellaneous/DemoDataPostRunDocument</a>|
|[Document](#Document)||<a href="DemoDataPostRunDocument.md" target="_blank">Miscellaneous/DemoDataPostRunDocument</a>|
|[DocumentTarget](#DocumentTarget)||<a href="DemoDataPostRunDocument.md" target="_blank">Miscellaneous/DemoDataPostRunDocument</a>|
|[RunStatus](#RunStatus)||<a href="DemoDataPostRunDocument.md" target="_blank">Miscellaneous/DemoDataPostRunDocument</a>|
|[CompletionTime](#CompletionTime)||<a href="DemoDataPostRunDocument.md" target="_blank">Miscellaneous/DemoDataPostRunDocument</a>|
|[FromDocumentId](#FromDocumentId)||<a href="DemoDataPostRunDocument.md" target="_blank">Miscellaneous/DemoDataPostRunDocument</a>|
|[ToDocumentId](#ToDocumentId)||<a href="DemoDataPostRunDocument.md" target="_blank">Miscellaneous/DemoDataPostRunDocument</a>|
|[FromDocumentDate](#FromDocumentDate)||<a href="DemoDataPostRunDocument.md" target="_blank">Miscellaneous/DemoDataPostRunDocument</a>|
|[ToDocumentDate](#ToDocumentDate)||<a href="DemoDataPostRunDocument.md" target="_blank">Miscellaneous/DemoDataPostRunDocument</a>|
|[DataAreaId](#DataAreaId)||<a href="DemoDataPostRunDocument.md" target="_blank">Miscellaneous/DemoDataPostRunDocument</a>|
|[Relationship_DemoDataPostRunRelationshipId](#Relationship_DemoDataPostRunRelationshipId)||<a href="DemoDataPostRunDocument.md" target="_blank">Miscellaneous/DemoDataPostRunDocument</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="DemoDataPostRunDocument.md" target="_blank">Miscellaneous/DemoDataPostRunDocument</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/DemoDataPostRunDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DemoDataPostRunDocument/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RunId name="RunId">RunId</a>

First included in: Miscellaneous/DemoDataPostRunDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RunId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Miscellaneous/DemoDataPostRunDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Document name="Document">Document</a>

First included in: Miscellaneous/DemoDataPostRunDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Document attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocumentTarget name="DocumentTarget">DocumentTarget</a>

First included in: Miscellaneous/DemoDataPostRunDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentTarget attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RunStatus name="RunStatus">RunStatus</a>

First included in: Miscellaneous/DemoDataPostRunDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RunStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CompletionTime name="CompletionTime">CompletionTime</a>

First included in: Miscellaneous/DemoDataPostRunDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompletionTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#FromDocumentId name="FromDocumentId">FromDocumentId</a>

First included in: Miscellaneous/DemoDataPostRunDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDocumentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToDocumentId name="ToDocumentId">ToDocumentId</a>

First included in: Miscellaneous/DemoDataPostRunDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDocumentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromDocumentDate name="FromDocumentDate">FromDocumentDate</a>

First included in: Miscellaneous/DemoDataPostRunDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDocumentDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ToDocumentDate name="ToDocumentDate">ToDocumentDate</a>

First included in: Miscellaneous/DemoDataPostRunDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDocumentDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/DemoDataPostRunDocument (this entity)  

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

### <a href=#Relationship_DemoDataPostRunRelationshipId name="Relationship_DemoDataPostRunRelationshipId">Relationship_DemoDataPostRunRelationshipId</a>

First included in: Miscellaneous/DemoDataPostRunDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DemoDataPostRunRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="DemoDataPostRun.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Miscellaneous/DemoDataPostRun.cdm.json/DemoDataPostRun</a></td><td><a href="DemoDataPostRun.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/DemoDataPostRunDocument (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
