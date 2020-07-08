---
title: LedgerJournalTrans_RCash in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Cash journal in WorksheetLine(LedgerJournalTrans_RCash)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/WorksheetLine/LedgerJournalTrans_RCash.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerJournalTrans_RCash/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cash journal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[CashDocId](#CashDocId)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[CashReceiptNumLV](#CashReceiptNumLV)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[DocType](#DocType)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[ExcludeExchAdj_PL](#ExcludeExchAdj_PL)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[LvCashReceiptTable](#LvCashReceiptTable)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[ManualRounding_HU](#ManualRounding_HU)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[RefRecId](#RefRecId)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[RoundOffCashAmount_HU](#RoundOffCashAmount_HU)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[TransRegDate_PL](#TransRegDate_PL)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[TransStatus](#TransStatus)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[CashCollBagNum_RU](#CashCollBagNum_RU)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[CashCollBankContributor_RU](#CashCollBankContributor_RU)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[CashCollCreditAccountNum_RU](#CashCollCreditAccountNum_RU)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[CashCollDebitAccountNum_RU](#CashCollDebitAccountNum_RU)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[CashCollStoreId_RU](#CashCollStoreId_RU)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[CashSourceCode_RU](#CashSourceCode_RU)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[CashSourceDescription_RU](#CashSourceDescription_RU)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[Relationship_LedgerJournalTransRelationshipId](#Relationship_LedgerJournalTransRelationshipId)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[Relationship_LvCashReceiptTableRelationshipId](#Relationship_LvCashReceiptTableRelationshipId)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[Relationship_CashCollBankGroup_RURelationshipId](#Relationship_CashCollBankGroup_RURelationshipId)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[Relationship_CashSourceCodeTable_RURelationshipId](#Relationship_CashSourceCodeTable_RURelationshipId)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerJournalTrans_RCash.md" target="_blank">WorksheetLine/LedgerJournalTrans_RCash</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerJournalTrans_RCash/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CashDocId name="CashDocId">CashDocId</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDocId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashReceiptNumLV name="CashReceiptNumLV">CashReceiptNumLV</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashReceiptNumLV attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocType name="DocType">DocType</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ExcludeExchAdj_PL name="ExcludeExchAdj_PL">ExcludeExchAdj_PL</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcludeExchAdj_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LvCashReceiptTable name="LvCashReceiptTable">LvCashReceiptTable</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LvCashReceiptTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ManualRounding_HU name="ManualRounding_HU">ManualRounding_HU</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manual rounding</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualRounding_HU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Manual rounding</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RefRecId name="RefRecId">RefRecId</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RoundOffCashAmount_HU name="RoundOffCashAmount_HU">RoundOffCashAmount_HU</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cash round-off</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundOffCashAmount_HU attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cash round-off</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransRegDate_PL name="TransRegDate_PL">TransRegDate_PL</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransRegDate_PL attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#TransStatus name="TransStatus">TransStatus</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CashCollBagNum_RU name="CashCollBagNum_RU">CashCollBagNum_RU</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashCollBagNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashCollBankContributor_RU name="CashCollBankContributor_RU">CashCollBankContributor_RU</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bank contributor</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashCollBankContributor_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bank contributor</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashCollCreditAccountNum_RU name="CashCollCreditAccountNum_RU">CashCollCreditAccountNum_RU</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashCollCreditAccountNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashCollDebitAccountNum_RU name="CashCollDebitAccountNum_RU">CashCollDebitAccountNum_RU</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Debit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashCollDebitAccountNum_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Debit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashCollStoreId_RU name="CashCollStoreId_RU">CashCollStoreId_RU</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashCollStoreId_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashSourceCode_RU name="CashSourceCode_RU">CashSourceCode_RU</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashSourceCode_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashSourceDescription_RU name="CashSourceDescription_RU">CashSourceDescription_RU</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashSourceDescription_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

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

### <a href=#Relationship_LedgerJournalTransRelationshipId name="Relationship_LedgerJournalTransRelationshipId">Relationship_LedgerJournalTransRelationshipId</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/WorksheetLine/LedgerJournalTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/WorksheetLine/LedgerJournalTrans.cdm.json/LedgerJournalTrans</a></td><td><a href="../../AccountingFoundation/WorksheetLine/LedgerJournalTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LvCashReceiptTableRelationshipId name="Relationship_LvCashReceiptTableRelationshipId">Relationship_LvCashReceiptTableRelationshipId</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LvCashReceiptTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/WorksheetHeader/LvCashReceiptTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/WorksheetHeader/LvCashReceiptTable.cdm.json/LvCashReceiptTable</a></td><td><a href="../../Bank/WorksheetHeader/LvCashReceiptTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CashCollBankGroup_RURelationshipId name="Relationship_CashCollBankGroup_RURelationshipId">Relationship_CashCollBankGroup_RURelationshipId</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CashCollBankGroup_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Group/BankGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/BankGroup.cdm.json/BankGroup</a></td><td><a href="../../Bank/Group/BankGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CashSourceCodeTable_RURelationshipId name="Relationship_CashSourceCodeTable_RURelationshipId">Relationship_CashSourceCodeTable_RURelationshipId</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CashSourceCodeTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Main/CashSourceCodeTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/CashSourceCodeTable_RU.cdm.json/CashSourceCodeTable_RU</a></td><td><a href="../../Bank/Main/CashSourceCodeTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/LedgerJournalTrans_RCash (this entity)  

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
