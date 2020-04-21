---
title: VendOutAttendingNote_PNRemittanceTmp - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# VendOutAttendingNote_PNRemittanceTmp

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsPayable/Transaction/VendOutAttendingNote_PNRemittanceTmp.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendOutAttendingNote_PNRemittanceTmp/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[AccountNum](#AccountNum)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[AmountCur](#AmountCur)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[BankAccountAddress](#BankAccountAddress)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[BankAccountName](#BankAccountName)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[CompanyAccount](#CompanyAccount)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[companyAddress](#companyAddress)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[companyCoRegNum](#companyCoRegNum)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[companyName](#companyName)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[CompanyPhone](#CompanyPhone)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[CompanyTelefax](#CompanyTelefax)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[County](#County)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[CurrencyCode](#CurrencyCode)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[DateOfCreation](#DateOfCreation)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[DueDate](#DueDate)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[FileId](#FileId)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[Invoice](#Invoice)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[PromissoryNoteID](#PromissoryNoteID)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[SessionId](#SessionId)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[sumAmount](#sumAmount)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[sumCurrencyCode](#sumCurrencyCode)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[Total](#Total)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[vendCity](#vendCity)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[vendName](#vendName)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[DataAreaId](#DataAreaId)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[Relationship_Currency_CurrencyCodeRelationshipId](#Relationship_Currency_CurrencyCodeRelationshipId)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[Relationship_CurrencySumRelationshipId](#Relationship_CurrencySumRelationshipId)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[Relationship_VendPromissoryNoteJourRelationshipId](#Relationship_VendPromissoryNoteJourRelationshipId)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="VendOutAttendingNote_PNRemittanceTmp.md" target="_blank">Transaction/VendOutAttendingNote_PNRemittanceTmp</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendOutAttendingNote_PNRemittanceTmp/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountNum name="AccountNum">AccountNum</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountCur name="AmountCur">AmountCur</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BankAccountAddress name="BankAccountAddress">BankAccountAddress</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankAccountName name="BankAccountName">BankAccountName</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankAccountName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyAccount name="CompanyAccount">CompanyAccount</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#companyAddress name="companyAddress">companyAddress</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the companyAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#companyCoRegNum name="companyCoRegNum">companyCoRegNum</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the companyCoRegNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#companyName name="companyName">companyName</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the companyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyPhone name="CompanyPhone">CompanyPhone</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyPhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyTelefax name="CompanyTelefax">CompanyTelefax</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyTelefax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#County name="County">County</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the County attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateOfCreation name="DateOfCreation">DateOfCreation</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateOfCreation attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DueDate name="DueDate">DueDate</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#FileId name="FileId">FileId</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Invoice name="Invoice">Invoice</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PromissoryNoteID name="PromissoryNoteID">PromissoryNoteID</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PromissoryNoteID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SessionId name="SessionId">SessionId</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#sumAmount name="sumAmount">sumAmount</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the sumAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#sumCurrencyCode name="sumCurrencyCode">sumCurrencyCode</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the sumCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Total name="Total">Total</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Total attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#vendCity name="vendCity">vendCity</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the vendCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#vendName name="vendName">vendName</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the vendName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

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

### <a href=#Relationship_Currency_CurrencyCodeRelationshipId name="Relationship_Currency_CurrencyCodeRelationshipId">Relationship_Currency_CurrencyCodeRelationshipId</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Currency_CurrencyCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencySumRelationshipId name="Relationship_CurrencySumRelationshipId">Relationship_CurrencySumRelationshipId</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencySumRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendPromissoryNoteJourRelationshipId name="Relationship_VendPromissoryNoteJourRelationshipId">Relationship_VendPromissoryNoteJourRelationshipId</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendPromissoryNoteJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Transaction/VendPromissoryNoteJour.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Transaction/VendPromissoryNoteJour.cdm.json/VendPromissoryNoteJour</a></td><td><a href="../../Bank/Transaction/VendPromissoryNoteJour.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/VendOutAttendingNote_PNRemittanceTmp (this entity)  

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
