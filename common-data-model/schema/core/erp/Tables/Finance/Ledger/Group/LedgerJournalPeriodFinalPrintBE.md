---
title: LedgerJournalPeriodFinalPrintBE - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# LedgerJournalPeriodFinalPrintBE

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/Ledger/Group/LedgerJournalPeriodFinalPrintBE.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerJournalPeriodFinalPrintBE/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerJournalPeriodFinalPrintBE.md" target="_blank">Group/LedgerJournalPeriodFinalPrintBE</a>|
|[Compressed](#Compressed)||<a href="LedgerJournalPeriodFinalPrintBE.md" target="_blank">Group/LedgerJournalPeriodFinalPrintBE</a>|
|[CreditTotal](#CreditTotal)||<a href="LedgerJournalPeriodFinalPrintBE.md" target="_blank">Group/LedgerJournalPeriodFinalPrintBE</a>|
|[DebitTotal](#DebitTotal)||<a href="LedgerJournalPeriodFinalPrintBE.md" target="_blank">Group/LedgerJournalPeriodFinalPrintBE</a>|
|[LedgerPostingJournalId](#LedgerPostingJournalId)||<a href="LedgerJournalPeriodFinalPrintBE.md" target="_blank">Group/LedgerJournalPeriodFinalPrintBE</a>|
|[Name](#Name)||<a href="LedgerJournalPeriodFinalPrintBE.md" target="_blank">Group/LedgerJournalPeriodFinalPrintBE</a>|
|[NumberLastPage](#NumberLastPage)||<a href="LedgerJournalPeriodFinalPrintBE.md" target="_blank">Group/LedgerJournalPeriodFinalPrintBE</a>|
|[PeriodEnd](#PeriodEnd)||<a href="LedgerJournalPeriodFinalPrintBE.md" target="_blank">Group/LedgerJournalPeriodFinalPrintBE</a>|
|[PeriodStart](#PeriodStart)||<a href="LedgerJournalPeriodFinalPrintBE.md" target="_blank">Group/LedgerJournalPeriodFinalPrintBE</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerJournalPeriodFinalPrintBE.md" target="_blank">Group/LedgerJournalPeriodFinalPrintBE</a>|
|[Relationship_LedgerPostingJournalRelationshipId](#Relationship_LedgerPostingJournalRelationshipId)||<a href="LedgerJournalPeriodFinalPrintBE.md" target="_blank">Group/LedgerJournalPeriodFinalPrintBE</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerJournalPeriodFinalPrintBE.md" target="_blank">Group/LedgerJournalPeriodFinalPrintBE</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/LedgerJournalPeriodFinalPrintBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerJournalPeriodFinalPrintBE/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Compressed name="Compressed">Compressed</a>

First included in: Group/LedgerJournalPeriodFinalPrintBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Compressed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditTotal name="CreditTotal">CreditTotal</a>

First included in: Group/LedgerJournalPeriodFinalPrintBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditTotal attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DebitTotal name="DebitTotal">DebitTotal</a>

First included in: Group/LedgerJournalPeriodFinalPrintBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitTotal attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LedgerPostingJournalId name="LedgerPostingJournalId">LedgerPostingJournalId</a>

First included in: Group/LedgerJournalPeriodFinalPrintBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerPostingJournalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Group/LedgerJournalPeriodFinalPrintBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberLastPage name="NumberLastPage">NumberLastPage</a>

First included in: Group/LedgerJournalPeriodFinalPrintBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberLastPage attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#PeriodEnd name="PeriodEnd">PeriodEnd</a>

First included in: Group/LedgerJournalPeriodFinalPrintBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodEnd attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#PeriodStart name="PeriodStart">PeriodStart</a>

First included in: Group/LedgerJournalPeriodFinalPrintBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodStart attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/LedgerJournalPeriodFinalPrintBE (this entity)  

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

### <a href=#Relationship_LedgerPostingJournalRelationshipId name="Relationship_LedgerPostingJournalRelationshipId">Relationship_LedgerPostingJournalRelationshipId</a>

First included in: Group/LedgerJournalPeriodFinalPrintBE (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerPostingJournalRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LedgerPostingJournal.md" target="_blank">/core/erp/Tables/Finance/Ledger/Group/LedgerPostingJournal.cdm.json/LedgerPostingJournal</a></td><td><a href="LedgerPostingJournal.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/LedgerJournalPeriodFinalPrintBE (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
