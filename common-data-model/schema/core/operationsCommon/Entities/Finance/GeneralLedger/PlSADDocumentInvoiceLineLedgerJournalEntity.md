---
title: PlSADDocumentInvoiceLineLedgerJournalEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Invoice lines for SAD document from general journal in GeneralLedger

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice lines for SAD document from general journal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Amount](#Amount)||<a href="PlSADDocumentInvoiceLineLedgerJournalEntity.md" target="_blank">GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity</a>|
|[InvoiceDate](#InvoiceDate)||<a href="PlSADDocumentInvoiceLineLedgerJournalEntity.md" target="_blank">GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity</a>|
|[Invoice](#Invoice)||<a href="PlSADDocumentInvoiceLineLedgerJournalEntity.md" target="_blank">GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity</a>|
|[LedgerAccount](#LedgerAccount)||<a href="PlSADDocumentInvoiceLineLedgerJournalEntity.md" target="_blank">GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity</a>|
|[SADDate](#SADDate)||<a href="PlSADDocumentInvoiceLineLedgerJournalEntity.md" target="_blank">GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity</a>|
|[Position](#Position)||<a href="PlSADDocumentInvoiceLineLedgerJournalEntity.md" target="_blank">GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity</a>|
|[ItemCommodityCode](#ItemCommodityCode)||<a href="PlSADDocumentInvoiceLineLedgerJournalEntity.md" target="_blank">GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity</a>|
|[SADNumber](#SADNumber)||<a href="PlSADDocumentInvoiceLineLedgerJournalEntity.md" target="_blank">GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity</a>|
|[LedgerAccountDisplayValue](#LedgerAccountDisplayValue)||<a href="PlSADDocumentInvoiceLineLedgerJournalEntity.md" target="_blank">GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity</a>|
|[RecordId](#RecordId)||<a href="PlSADDocumentInvoiceLineLedgerJournalEntity.md" target="_blank">GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity</a>|
|[Relationship_LedgerAccountCombinationRelationshipId](#Relationship_LedgerAccountCombinationRelationshipId)||<a href="PlSADDocumentInvoiceLineLedgerJournalEntity.md" target="_blank">GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity</a>|
|[Relationship_InvoiceForSADDocumentRelationshipId](#Relationship_InvoiceForSADDocumentRelationshipId)||<a href="PlSADDocumentInvoiceLineLedgerJournalEntity.md" target="_blank">GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity</a>|
|[Relationship_SADDocumentLineRelationshipId](#Relationship_SADDocumentLineRelationshipId)||<a href="PlSADDocumentInvoiceLineLedgerJournalEntity.md" target="_blank">GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity</a>|
|[BackingTable_PlSADFinanceInvTransRelationshipId](#BackingTable_PlSADFinanceInvTransRelationshipId)||<a href="PlSADDocumentInvoiceLineLedgerJournalEntity.md" target="_blank">GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PlSADDocumentInvoiceLineLedgerJournalEntity.md" target="_blank">GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity</a>|

### <a href=#Amount name="Amount">Amount</a>

First included in: GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDate name="InvoiceDate">InvoiceDate</a>

First included in: GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Invoice name="Invoice">Invoice</a>

First included in: GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerAccount name="LedgerAccount">LedgerAccount</a>

First included in: GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SADDate name="SADDate">SADDate</a>

First included in: GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SADDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Position name="Position">Position</a>

First included in: GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Position attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemCommodityCode name="ItemCommodityCode">ItemCommodityCode</a>

First included in: GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemCommodityCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SADNumber name="SADNumber">SADNumber</a>

First included in: GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SADNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerAccountDisplayValue name="LedgerAccountDisplayValue">LedgerAccountDisplayValue</a>

First included in: GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecordId name="RecordId">RecordId</a>

First included in: GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerAccountCombinationRelationshipId name="Relationship_LedgerAccountCombinationRelationshipId">Relationship_LedgerAccountCombinationRelationshipId</a>

First included in: GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAccountCombinationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InvoiceForSADDocumentRelationshipId name="Relationship_InvoiceForSADDocumentRelationshipId">Relationship_InvoiceForSADDocumentRelationshipId</a>

First included in: GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InvoiceForSADDocumentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SADDocumentLineRelationshipId name="Relationship_SADDocumentLineRelationshipId">Relationship_SADDocumentLineRelationshipId</a>

First included in: GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SADDocumentLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PlSADFinanceInvTransRelationshipId name="BackingTable_PlSADFinanceInvTransRelationshipId">BackingTable_PlSADFinanceInvTransRelationshipId</a>

First included in: GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PlSADFinanceInvTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsReceivable/Transaction/PlSADFinanceInvTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/PlSADFinanceInvTrans.cdm.json/PlSADFinanceInvTrans</a></td><td><a href="../../../Tables/Finance/AccountsReceivable/Transaction/PlSADFinanceInvTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/PlSADDocumentInvoiceLineLedgerJournalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
