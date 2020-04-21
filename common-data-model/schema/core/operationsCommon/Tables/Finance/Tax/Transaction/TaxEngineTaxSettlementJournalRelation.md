---
title: TaxEngineTaxSettlementJournalRelation - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# TaxEngineTaxSettlementJournalRelation

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxEngineTaxSettlementJournalRelation.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxEngineTaxSettlementJournalRelation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxEngineTaxSettlementJournalRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJournalRelation</a>|
|[CanBeReversed](#CanBeReversed)||<a href="TaxEngineTaxSettlementJournalRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJournalRelation</a>|
|[CreditParentTransRecId](#CreditParentTransRecId)||<a href="TaxEngineTaxSettlementJournalRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJournalRelation</a>|
|[CreditTransactionRecId](#CreditTransactionRecId)||<a href="TaxEngineTaxSettlementJournalRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJournalRelation</a>|
|[CreditTransactionTableId](#CreditTransactionTableId)||<a href="TaxEngineTaxSettlementJournalRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJournalRelation</a>|
|[DebitParentTransRecId](#DebitParentTransRecId)||<a href="TaxEngineTaxSettlementJournalRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJournalRelation</a>|
|[DebitTransactionRecId](#DebitTransactionRecId)||<a href="TaxEngineTaxSettlementJournalRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJournalRelation</a>|
|[DebitTransactionTableId](#DebitTransactionTableId)||<a href="TaxEngineTaxSettlementJournalRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJournalRelation</a>|
|[TaxEngineTaxJournal](#TaxEngineTaxJournal)||<a href="TaxEngineTaxSettlementJournalRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJournalRelation</a>|
|[TransDate](#TransDate)||<a href="TaxEngineTaxSettlementJournalRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJournalRelation</a>|
|[Voucher](#Voucher)||<a href="TaxEngineTaxSettlementJournalRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJournalRelation</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxEngineTaxSettlementJournalRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJournalRelation</a>|
|[Relationship_TaxEngineTaxJournalRelationshipId](#Relationship_TaxEngineTaxJournalRelationshipId)||<a href="TaxEngineTaxSettlementJournalRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJournalRelation</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxEngineTaxSettlementJournalRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJournalRelation</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/TaxEngineTaxSettlementJournalRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxEngineTaxSettlementJournalRelation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CanBeReversed name="CanBeReversed">CanBeReversed</a>

First included in: Transaction/TaxEngineTaxSettlementJournalRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanBeReversed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditParentTransRecId name="CreditParentTransRecId">CreditParentTransRecId</a>

First included in: Transaction/TaxEngineTaxSettlementJournalRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditParentTransRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CreditTransactionRecId name="CreditTransactionRecId">CreditTransactionRecId</a>

First included in: Transaction/TaxEngineTaxSettlementJournalRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditTransactionRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CreditTransactionTableId name="CreditTransactionTableId">CreditTransactionTableId</a>

First included in: Transaction/TaxEngineTaxSettlementJournalRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditTransactionTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DebitParentTransRecId name="DebitParentTransRecId">DebitParentTransRecId</a>

First included in: Transaction/TaxEngineTaxSettlementJournalRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitParentTransRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DebitTransactionRecId name="DebitTransactionRecId">DebitTransactionRecId</a>

First included in: Transaction/TaxEngineTaxSettlementJournalRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitTransactionRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DebitTransactionTableId name="DebitTransactionTableId">DebitTransactionTableId</a>

First included in: Transaction/TaxEngineTaxSettlementJournalRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DebitTransactionTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxEngineTaxJournal name="TaxEngineTaxJournal">TaxEngineTaxJournal</a>

First included in: Transaction/TaxEngineTaxSettlementJournalRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxEngineTaxJournal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Transaction/TaxEngineTaxSettlementJournalRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: Transaction/TaxEngineTaxSettlementJournalRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/TaxEngineTaxSettlementJournalRelation (this entity)  

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

### <a href=#Relationship_TaxEngineTaxJournalRelationshipId name="Relationship_TaxEngineTaxJournalRelationshipId">Relationship_TaxEngineTaxJournalRelationshipId</a>

First included in: Transaction/TaxEngineTaxSettlementJournalRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxEngineTaxJournalRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/TaxEngineTaxJournal.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/WorksheetHeader/TaxEngineTaxJournal.cdm.json/TaxEngineTaxJournal</a></td><td><a href="../WorksheetHeader/TaxEngineTaxJournal.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/TaxEngineTaxSettlementJournalRelation (this entity)  

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
