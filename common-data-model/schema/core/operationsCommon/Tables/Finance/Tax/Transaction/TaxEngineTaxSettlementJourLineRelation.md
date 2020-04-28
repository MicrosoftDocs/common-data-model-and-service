---
title: TaxEngineTaxSettlementJourLineRelation - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Tax engine tax settlement journal line relation

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxEngineTaxSettlementJourLineRelation.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxEngineTaxSettlementJourLineRelation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax engine tax settlement journal line relation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxEngineTaxSettlementJourLineRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJourLineRelation</a>|
|[JournalRelation](#JournalRelation)||<a href="TaxEngineTaxSettlementJourLineRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJourLineRelation</a>|
|[TaxEngineTaxJournal](#TaxEngineTaxJournal)||<a href="TaxEngineTaxSettlementJourLineRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJourLineRelation</a>|
|[TaxEngineTaxJournalLine](#TaxEngineTaxJournalLine)||<a href="TaxEngineTaxSettlementJourLineRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJourLineRelation</a>|
|[SettledAccountingAmount](#SettledAccountingAmount)||<a href="TaxEngineTaxSettlementJourLineRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJourLineRelation</a>|
|[SettledTransactionAmount](#SettledTransactionAmount)||<a href="TaxEngineTaxSettlementJourLineRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJourLineRelation</a>|
|[TaxMeasure](#TaxMeasure)||<a href="TaxEngineTaxSettlementJourLineRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJourLineRelation</a>|
|[TransactionLineRecId](#TransactionLineRecId)||<a href="TaxEngineTaxSettlementJourLineRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJourLineRelation</a>|
|[TransactionLineTableId](#TransactionLineTableId)||<a href="TaxEngineTaxSettlementJourLineRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJourLineRelation</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxEngineTaxSettlementJourLineRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJourLineRelation</a>|
|[Relationship_TaxEngineTaxSettlementJournalRelationRelationshipId](#Relationship_TaxEngineTaxSettlementJournalRelationRelationshipId)||<a href="TaxEngineTaxSettlementJourLineRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJourLineRelation</a>|
|[Relationship_TaxEngineTaxJournalRelationshipId](#Relationship_TaxEngineTaxJournalRelationshipId)||<a href="TaxEngineTaxSettlementJourLineRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJourLineRelation</a>|
|[Relationship_TaxEngineTaxJournalLineRelationshipId](#Relationship_TaxEngineTaxJournalLineRelationshipId)||<a href="TaxEngineTaxSettlementJourLineRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJourLineRelation</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxEngineTaxSettlementJourLineRelation.md" target="_blank">Transaction/TaxEngineTaxSettlementJourLineRelation</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/TaxEngineTaxSettlementJourLineRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxEngineTaxSettlementJourLineRelation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#JournalRelation name="JournalRelation">JournalRelation</a>

First included in: Transaction/TaxEngineTaxSettlementJourLineRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalRelation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxEngineTaxJournal name="TaxEngineTaxJournal">TaxEngineTaxJournal</a>

First included in: Transaction/TaxEngineTaxSettlementJourLineRelation (this entity)  

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

### <a href=#TaxEngineTaxJournalLine name="TaxEngineTaxJournalLine">TaxEngineTaxJournalLine</a>

First included in: Transaction/TaxEngineTaxSettlementJourLineRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxEngineTaxJournalLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SettledAccountingAmount name="SettledAccountingAmount">SettledAccountingAmount</a>

First included in: Transaction/TaxEngineTaxSettlementJourLineRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettledAccountingAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SettledTransactionAmount name="SettledTransactionAmount">SettledTransactionAmount</a>

First included in: Transaction/TaxEngineTaxSettlementJourLineRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettledTransactionAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxMeasure name="TaxMeasure">TaxMeasure</a>

First included in: Transaction/TaxEngineTaxSettlementJourLineRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxMeasure attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TransactionLineRecId name="TransactionLineRecId">TransactionLineRecId</a>

First included in: Transaction/TaxEngineTaxSettlementJourLineRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionLineRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TransactionLineTableId name="TransactionLineTableId">TransactionLineTableId</a>

First included in: Transaction/TaxEngineTaxSettlementJourLineRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionLineTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/TaxEngineTaxSettlementJourLineRelation (this entity)  

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

### <a href=#Relationship_TaxEngineTaxSettlementJournalRelationRelationshipId name="Relationship_TaxEngineTaxSettlementJournalRelationRelationshipId">Relationship_TaxEngineTaxSettlementJournalRelationRelationshipId</a>

First included in: Transaction/TaxEngineTaxSettlementJourLineRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxEngineTaxSettlementJournalRelationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxEngineTaxSettlementJournalRelation.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Transaction/TaxEngineTaxSettlementJournalRelation.cdm.json/TaxEngineTaxSettlementJournalRelation</a></td><td><a href="TaxEngineTaxSettlementJournalRelation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxEngineTaxJournalRelationshipId name="Relationship_TaxEngineTaxJournalRelationshipId">Relationship_TaxEngineTaxJournalRelationshipId</a>

First included in: Transaction/TaxEngineTaxSettlementJourLineRelation (this entity)  

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

### <a href=#Relationship_TaxEngineTaxJournalLineRelationshipId name="Relationship_TaxEngineTaxJournalLineRelationshipId">Relationship_TaxEngineTaxJournalLineRelationshipId</a>

First included in: Transaction/TaxEngineTaxSettlementJourLineRelation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxEngineTaxJournalLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/TaxEngineTaxJournalLine.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/WorksheetLine/TaxEngineTaxJournalLine.cdm.json/TaxEngineTaxJournalLine</a></td><td><a href="../WorksheetLine/TaxEngineTaxJournalLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/TaxEngineTaxSettlementJourLineRelation (this entity)  

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
