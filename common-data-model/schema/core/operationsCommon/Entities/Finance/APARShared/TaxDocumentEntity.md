---
title: TaxDocumentEntity in APARShared - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Tax document in APARShared(TaxDocumentEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/APARShared/TaxDocumentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax document</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[TaxDocumentNumber](#TaxDocumentNumber)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[TaxDocumentDate](#TaxDocumentDate)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[Amount](#Amount)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[TaxAmount](#TaxAmount)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[AmountInTransactionCurrency](#AmountInTransactionCurrency)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[TaxAmountInCurrency](#TaxAmountInCurrency)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[TaxDocumentTransactionTypeOfTax](#TaxDocumentTransactionTypeOfTax)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[TaxDocumentTransactionTaxValue](#TaxDocumentTransactionTaxValue)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[TaxDocumentTransactionAmount](#TaxDocumentTransactionAmount)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[TaxDocumentTransactionTaxAmount](#TaxDocumentTransactionTaxAmount)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[TaxDocumentTransactionAmountInTransactionCurrency](#TaxDocumentTransactionAmountInTransactionCurrency)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[TaxDocumentTransactionTaxAmountInCurrency](#TaxDocumentTransactionTaxAmountInCurrency)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[TaxCreditMemoNumber](#TaxCreditMemoNumber)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[TaxCreditMemoDate](#TaxCreditMemoDate)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[TaxCreditMemoTransactionTypeOfTax](#TaxCreditMemoTransactionTypeOfTax)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[TaxCreditMemoTransactionTaxValue](#TaxCreditMemoTransactionTaxValue)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[TaxCreditMemoTransactionAmount](#TaxCreditMemoTransactionAmount)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[TaxCreditMemoTransactionTaxAmount](#TaxCreditMemoTransactionTaxAmount)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[TaxCreditMemoTransactionAmountInTransactionCurrency](#TaxCreditMemoTransactionAmountInTransactionCurrency)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[TaxCreditMemoTransactionTaxAmountInCurrency](#TaxCreditMemoTransactionTaxAmountInCurrency)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[CustVendTransTableId](#CustVendTransTableId)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[BackingTable_CzTaxDocumentTableRelationshipId](#BackingTable_CzTaxDocumentTableRelationshipId)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TaxDocumentEntity.md" target="_blank">APARShared/TaxDocumentEntity</a>|

### <a href=#TaxDocumentNumber name="TaxDocumentNumber">TaxDocumentNumber</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxDocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxDocumentDate name="TaxDocumentDate">TaxDocumentDate</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxDocumentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Amount name="Amount">Amount</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

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

### <a href=#TaxAmount name="TaxAmount">TaxAmount</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountInTransactionCurrency name="AmountInTransactionCurrency">AmountInTransactionCurrency</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInTransactionCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountInCurrency name="TaxAmountInCurrency">TaxAmountInCurrency</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountInCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxDocumentTransactionTypeOfTax name="TaxDocumentTransactionTypeOfTax">TaxDocumentTransactionTypeOfTax</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxDocumentTransactionTypeOfTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxDocumentTransactionTaxValue name="TaxDocumentTransactionTaxValue">TaxDocumentTransactionTaxValue</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxDocumentTransactionTaxValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxDocumentTransactionAmount name="TaxDocumentTransactionAmount">TaxDocumentTransactionAmount</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxDocumentTransactionAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxDocumentTransactionTaxAmount name="TaxDocumentTransactionTaxAmount">TaxDocumentTransactionTaxAmount</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxDocumentTransactionTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxDocumentTransactionAmountInTransactionCurrency name="TaxDocumentTransactionAmountInTransactionCurrency">TaxDocumentTransactionAmountInTransactionCurrency</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxDocumentTransactionAmountInTransactionCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxDocumentTransactionTaxAmountInCurrency name="TaxDocumentTransactionTaxAmountInCurrency">TaxDocumentTransactionTaxAmountInCurrency</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxDocumentTransactionTaxAmountInCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCreditMemoNumber name="TaxCreditMemoNumber">TaxCreditMemoNumber</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCreditMemoNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCreditMemoDate name="TaxCreditMemoDate">TaxCreditMemoDate</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCreditMemoDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCreditMemoTransactionTypeOfTax name="TaxCreditMemoTransactionTypeOfTax">TaxCreditMemoTransactionTypeOfTax</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCreditMemoTransactionTypeOfTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCreditMemoTransactionTaxValue name="TaxCreditMemoTransactionTaxValue">TaxCreditMemoTransactionTaxValue</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCreditMemoTransactionTaxValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCreditMemoTransactionAmount name="TaxCreditMemoTransactionAmount">TaxCreditMemoTransactionAmount</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCreditMemoTransactionAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCreditMemoTransactionTaxAmount name="TaxCreditMemoTransactionTaxAmount">TaxCreditMemoTransactionTaxAmount</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCreditMemoTransactionTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCreditMemoTransactionAmountInTransactionCurrency name="TaxCreditMemoTransactionAmountInTransactionCurrency">TaxCreditMemoTransactionAmountInTransactionCurrency</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCreditMemoTransactionAmountInTransactionCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCreditMemoTransactionTaxAmountInCurrency name="TaxCreditMemoTransactionTaxAmountInCurrency">TaxCreditMemoTransactionTaxAmountInCurrency</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCreditMemoTransactionTaxAmountInCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustVendTransTableId name="CustVendTransTableId">CustVendTransTableId</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustVendTransTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CzTaxDocumentTableRelationshipId name="BackingTable_CzTaxDocumentTableRelationshipId">BackingTable_CzTaxDocumentTableRelationshipId</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CzTaxDocumentTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Tax/Transaction/CzTaxDocumentTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Transaction/CzTaxDocumentTable.cdm.json/CzTaxDocumentTable</a></td><td><a href="../../../Tables/Finance/Tax/Transaction/CzTaxDocumentTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: APARShared/TaxDocumentEntity (this entity)  

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
