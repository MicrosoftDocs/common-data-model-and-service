---
title: LedgerJournalParmPost - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# LedgerJournalParmPost

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountingFoundation/Worksheet/LedgerJournalParmPost.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerJournalParmPost/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerJournalParmPost.md" target="_blank">Worksheet/LedgerJournalParmPost</a>|
|[ExecutedDateTime](#ExecutedDateTime)||<a href="LedgerJournalParmPost.md" target="_blank">Worksheet/LedgerJournalParmPost</a>|
|[JobStatus](#JobStatus)||<a href="LedgerJournalParmPost.md" target="_blank">Worksheet/LedgerJournalParmPost</a>|
|[LateSelection](#LateSelection)||<a href="LedgerJournalParmPost.md" target="_blank">Worksheet/LedgerJournalParmPost</a>|
|[LateSelectionQuery](#LateSelectionQuery)||<a href="LedgerJournalParmPost.md" target="_blank">Worksheet/LedgerJournalParmPost</a>|
|[LedgerJournalId](#LedgerJournalId)||<a href="LedgerJournalParmPost.md" target="_blank">Worksheet/LedgerJournalParmPost</a>|
|[LedgerJournalType](#LedgerJournalType)||<a href="LedgerJournalParmPost.md" target="_blank">Worksheet/LedgerJournalParmPost</a>|
|[LineNum](#LineNum)||<a href="LedgerJournalParmPost.md" target="_blank">Worksheet/LedgerJournalParmPost</a>|
|[ParmId](#ParmId)||<a href="LedgerJournalParmPost.md" target="_blank">Worksheet/LedgerJournalParmPost</a>|
|[TransferErrors](#TransferErrors)||<a href="LedgerJournalParmPost.md" target="_blank">Worksheet/LedgerJournalParmPost</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerJournalParmPost.md" target="_blank">Worksheet/LedgerJournalParmPost</a>|
|[Relationship_LedgerJournalTable_LedgerJournalIdRelationshipId](#Relationship_LedgerJournalTable_LedgerJournalIdRelationshipId)||<a href="LedgerJournalParmPost.md" target="_blank">Worksheet/LedgerJournalParmPost</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerJournalParmPost.md" target="_blank">Worksheet/LedgerJournalParmPost</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Worksheet/LedgerJournalParmPost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerJournalParmPost/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExecutedDateTime name="ExecutedDateTime">ExecutedDateTime</a>

First included in: Worksheet/LedgerJournalParmPost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExecutedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#JobStatus name="JobStatus">JobStatus</a>

First included in: Worksheet/LedgerJournalParmPost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#LateSelection name="LateSelection">LateSelection</a>

First included in: Worksheet/LedgerJournalParmPost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LateSelection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LateSelectionQuery name="LateSelectionQuery">LateSelectionQuery</a>

First included in: Worksheet/LedgerJournalParmPost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LateSelectionQuery attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerJournalId name="LedgerJournalId">LedgerJournalId</a>

First included in: Worksheet/LedgerJournalParmPost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerJournalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerJournalType name="LedgerJournalType">LedgerJournalType</a>

First included in: Worksheet/LedgerJournalParmPost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerJournalType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Worksheet/LedgerJournalParmPost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ParmId name="ParmId">ParmId</a>

First included in: Worksheet/LedgerJournalParmPost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParmId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferErrors name="TransferErrors">TransferErrors</a>

First included in: Worksheet/LedgerJournalParmPost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferErrors attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Worksheet/LedgerJournalParmPost (this entity)  

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

### <a href=#Relationship_LedgerJournalTable_LedgerJournalIdRelationshipId name="Relationship_LedgerJournalTable_LedgerJournalIdRelationshipId">Relationship_LedgerJournalTable_LedgerJournalIdRelationshipId</a>

First included in: Worksheet/LedgerJournalParmPost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalTable_LedgerJournalIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/LedgerJournalTable.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/WorksheetHeader/LedgerJournalTable.cdm.json/LedgerJournalTable</a></td><td><a href="../WorksheetHeader/LedgerJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Worksheet/LedgerJournalParmPost (this entity)  

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
