---
title: BudgetSource - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# BudgetSource

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/Budget/Transaction/BudgetSource.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetSource/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[BudgetCheckGroup](#BudgetCheckGroup)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[BudgetCheckGroupSequence](#BudgetCheckGroupSequence)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[BudgetControlSourceIntegrator](#BudgetControlSourceIntegrator)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[BudgetSourceType](#BudgetSourceType)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[BudgetTransactionLine](#BudgetTransactionLine)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[CheckResult](#CheckResult)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[CheckResultErrorWarning](#CheckResultErrorWarning)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[CheckResultErrorWarningType](#CheckResultErrorWarningType)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[IsDeletePending](#IsDeletePending)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[IsOverrunApproved](#IsOverrunApproved)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[LedgerEntryGeneralJournalEntry](#LedgerEntryGeneralJournalEntry)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[LedgerEntryJournalLegalEntity](#LedgerEntryJournalLegalEntity)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[LedgerEntryJournalNumber](#LedgerEntryJournalNumber)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[LedgerEntryJournalReferenceNumber](#LedgerEntryJournalReferenceNumber)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[SourceDocumentLine](#SourceDocumentLine)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[Relationship_BudgetTransactionLineRelationshipId](#Relationship_BudgetTransactionLineRelationshipId)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[Relationship_GeneralJournalEntryRelationshipId](#Relationship_GeneralJournalEntryRelationshipId)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[Relationship_LegalEntityRelationshipId](#Relationship_LegalEntityRelationshipId)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|
|[Relationship_SourceDocumentLineRelationshipId](#Relationship_SourceDocumentLineRelationshipId)||<a href="BudgetSource.md" target="_blank">Transaction/BudgetSource</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetSource/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetCheckGroup name="BudgetCheckGroup">BudgetCheckGroup</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetCheckGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetCheckGroupSequence name="BudgetCheckGroupSequence">BudgetCheckGroupSequence</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetCheckGroupSequence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetControlSourceIntegrator name="BudgetControlSourceIntegrator">BudgetControlSourceIntegrator</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetControlSourceIntegrator attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BudgetSourceType name="BudgetSourceType">BudgetSourceType</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetSourceType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BudgetTransactionLine name="BudgetTransactionLine">BudgetTransactionLine</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetTransactionLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CheckResult name="CheckResult">CheckResult</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckResult attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CheckResultErrorWarning name="CheckResultErrorWarning">CheckResultErrorWarning</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckResultErrorWarning attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CheckResultErrorWarningType name="CheckResultErrorWarningType">CheckResultErrorWarningType</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckResultErrorWarningType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsDeletePending name="IsDeletePending">IsDeletePending</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeletePending attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsOverrunApproved name="IsOverrunApproved">IsOverrunApproved</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOverrunApproved attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LedgerEntryGeneralJournalEntry name="LedgerEntryGeneralJournalEntry">LedgerEntryGeneralJournalEntry</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerEntryGeneralJournalEntry attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerEntryJournalLegalEntity name="LedgerEntryJournalLegalEntity">LedgerEntryJournalLegalEntity</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerEntryJournalLegalEntity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerEntryJournalNumber name="LedgerEntryJournalNumber">LedgerEntryJournalNumber</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerEntryJournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerEntryJournalReferenceNumber name="LedgerEntryJournalReferenceNumber">LedgerEntryJournalReferenceNumber</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerEntryJournalReferenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceDocumentLine name="SourceDocumentLine">SourceDocumentLine</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceDocumentLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_BudgetTransactionLineRelationshipId name="Relationship_BudgetTransactionLineRelationshipId">Relationship_BudgetTransactionLineRelationshipId</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetTransactionLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/BudgetTransactionLine.md" target="_blank">/core/erp/Tables/Finance/Budget/WorksheetLine/BudgetTransactionLine.cdm.json/BudgetTransactionLine</a></td><td><a href="../WorksheetLine/BudgetTransactionLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_GeneralJournalEntryRelationshipId name="Relationship_GeneralJournalEntryRelationshipId">Relationship_GeneralJournalEntryRelationshipId</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_GeneralJournalEntryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/TransactionHeader/GeneralJournalEntry.md" target="_blank">/core/erp/Tables/Finance/Ledger/TransactionHeader/GeneralJournalEntry.cdm.json/GeneralJournalEntry</a></td><td><a href="../../Ledger/TransactionHeader/GeneralJournalEntry.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LegalEntityRelationshipId name="Relationship_LegalEntityRelationshipId">Relationship_LegalEntityRelationshipId</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LegalEntityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SourceDocumentLineRelationshipId name="Relationship_SourceDocumentLineRelationshipId">Relationship_SourceDocumentLineRelationshipId</a>

First included in: Transaction/BudgetSource (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SourceDocumentLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/TransactionLine/SourceDocumentLine.md" target="_blank">/core/erp/Tables/Finance/AccountingFoundation/TransactionLine/SourceDocumentLine.cdm.json/SourceDocumentLine</a></td><td><a href="../../AccountingFoundation/TransactionLine/SourceDocumentLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
