---
title: DimensionFocusUnprocessedTransactionsSim_IT - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Dimension set unprocessed transactions

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/Transaction/DimensionFocusUnprocessedTransactionsSim_IT.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DimensionFocusUnprocessedTransactionsSim_IT/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Dimension set unprocessed transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="DimensionFocusUnprocessedTransactionsSim_IT.md" target="_blank">Transaction/DimensionFocusUnprocessedTransactionsSim_IT</a>|
|[FocusDimensionHierarchy](#FocusDimensionHierarchy)||<a href="DimensionFocusUnprocessedTransactionsSim_IT.md" target="_blank">Transaction/DimensionFocusUnprocessedTransactionsSim_IT</a>|
|[GeneralJournalEntry](#GeneralJournalEntry)||<a href="DimensionFocusUnprocessedTransactionsSim_IT.md" target="_blank">Transaction/DimensionFocusUnprocessedTransactionsSim_IT</a>|
|[State](#State)||<a href="DimensionFocusUnprocessedTransactionsSim_IT.md" target="_blank">Transaction/DimensionFocusUnprocessedTransactionsSim_IT</a>|
|[Relationship_FocusDimensionHierarchyRelationshipId](#Relationship_FocusDimensionHierarchyRelationshipId)||<a href="DimensionFocusUnprocessedTransactionsSim_IT.md" target="_blank">Transaction/DimensionFocusUnprocessedTransactionsSim_IT</a>|
|[Relationship_GeneralJournalEntrySimRelationshipId](#Relationship_GeneralJournalEntrySimRelationshipId)||<a href="DimensionFocusUnprocessedTransactionsSim_IT.md" target="_blank">Transaction/DimensionFocusUnprocessedTransactionsSim_IT</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/DimensionFocusUnprocessedTransactionsSim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[DimensionFocusUnprocessedTransactionsSim_IT/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FocusDimensionHierarchy name="FocusDimensionHierarchy">FocusDimensionHierarchy</a>

First included in: Transaction/DimensionFocusUnprocessedTransactionsSim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FocusDimensionHierarchy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#GeneralJournalEntry name="GeneralJournalEntry">GeneralJournalEntry</a>

First included in: Transaction/DimensionFocusUnprocessedTransactionsSim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneralJournalEntry attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#State name="State">State</a>

First included in: Transaction/DimensionFocusUnprocessedTransactionsSim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the State attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_FocusDimensionHierarchyRelationshipId name="Relationship_FocusDimensionHierarchyRelationshipId">Relationship_FocusDimensionHierarchyRelationshipId</a>

First included in: Transaction/DimensionFocusUnprocessedTransactionsSim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FocusDimensionHierarchyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Group/DimensionHierarchy.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Group/DimensionHierarchy.cdm.json/DimensionHierarchy</a></td><td><a href="../../FinancialDimensions/Group/DimensionHierarchy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_GeneralJournalEntrySimRelationshipId name="Relationship_GeneralJournalEntrySimRelationshipId">Relationship_GeneralJournalEntrySimRelationshipId</a>

First included in: Transaction/DimensionFocusUnprocessedTransactionsSim_IT (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_GeneralJournalEntrySimRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../TransactionHeader/GeneralJournalEntrySim_IT.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/TransactionHeader/GeneralJournalEntrySim_IT.cdm.json/GeneralJournalEntrySim_IT</a></td><td><a href="../TransactionHeader/GeneralJournalEntrySim_IT.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
