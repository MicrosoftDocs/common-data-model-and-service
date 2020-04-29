---
title: CustBillingClassificationEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Billing Classification

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/CustBillingClassificationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Billing Classification</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[InvoiceNumber](#InvoiceNumber)||<a href="CustBillingClassificationEntity.md" target="_blank">AccountsReceivable/CustBillingClassificationEntity</a>|
|[BillingClassification](#BillingClassification)||<a href="CustBillingClassificationEntity.md" target="_blank">AccountsReceivable/CustBillingClassificationEntity</a>|
|[CollectionLetterSequence](#CollectionLetterSequence)||<a href="CustBillingClassificationEntity.md" target="_blank">AccountsReceivable/CustBillingClassificationEntity</a>|
|[CreditNoteNumber](#CreditNoteNumber)||<a href="CustBillingClassificationEntity.md" target="_blank">AccountsReceivable/CustBillingClassificationEntity</a>|
|[CustInterestCode](#CustInterestCode)||<a href="CustBillingClassificationEntity.md" target="_blank">AccountsReceivable/CustBillingClassificationEntity</a>|
|[Description](#Description)||<a href="CustBillingClassificationEntity.md" target="_blank">AccountsReceivable/CustBillingClassificationEntity</a>|
|[TermsOfPayment](#TermsOfPayment)||<a href="CustBillingClassificationEntity.md" target="_blank">AccountsReceivable/CustBillingClassificationEntity</a>|
|[RestrictSettlementOfCreditNotes](#RestrictSettlementOfCreditNotes)||<a href="CustBillingClassificationEntity.md" target="_blank">AccountsReceivable/CustBillingClassificationEntity</a>|
|[Priority](#Priority)||<a href="CustBillingClassificationEntity.md" target="_blank">AccountsReceivable/CustBillingClassificationEntity</a>|
|[UseCollectionLetterSequenceFromPostingProfile](#UseCollectionLetterSequenceFromPostingProfile)||<a href="CustBillingClassificationEntity.md" target="_blank">AccountsReceivable/CustBillingClassificationEntity</a>|
|[UseInterestCodeFromPostingProfile](#UseInterestCodeFromPostingProfile)||<a href="CustBillingClassificationEntity.md" target="_blank">AccountsReceivable/CustBillingClassificationEntity</a>|
|[InterestCode](#InterestCode)||<a href="CustBillingClassificationEntity.md" target="_blank">AccountsReceivable/CustBillingClassificationEntity</a>|
|[BackingTable_CustBillingClassificationRelationshipId](#BackingTable_CustBillingClassificationRelationshipId)||<a href="CustBillingClassificationEntity.md" target="_blank">AccountsReceivable/CustBillingClassificationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CustBillingClassificationEntity.md" target="_blank">AccountsReceivable/CustBillingClassificationEntity</a>|

### <a href=#InvoiceNumber name="InvoiceNumber">InvoiceNumber</a>

First included in: AccountsReceivable/CustBillingClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillingClassification name="BillingClassification">BillingClassification</a>

First included in: AccountsReceivable/CustBillingClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillingClassification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CollectionLetterSequence name="CollectionLetterSequence">CollectionLetterSequence</a>

First included in: AccountsReceivable/CustBillingClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CollectionLetterSequence attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditNoteNumber name="CreditNoteNumber">CreditNoteNumber</a>

First included in: AccountsReceivable/CustBillingClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditNoteNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustInterestCode name="CustInterestCode">CustInterestCode</a>

First included in: AccountsReceivable/CustBillingClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustInterestCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: AccountsReceivable/CustBillingClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TermsOfPayment name="TermsOfPayment">TermsOfPayment</a>

First included in: AccountsReceivable/CustBillingClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TermsOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RestrictSettlementOfCreditNotes name="RestrictSettlementOfCreditNotes">RestrictSettlementOfCreditNotes</a>

First included in: AccountsReceivable/CustBillingClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RestrictSettlementOfCreditNotes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Priority name="Priority">Priority</a>

First included in: AccountsReceivable/CustBillingClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Priority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseCollectionLetterSequenceFromPostingProfile name="UseCollectionLetterSequenceFromPostingProfile">UseCollectionLetterSequenceFromPostingProfile</a>

First included in: AccountsReceivable/CustBillingClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseCollectionLetterSequenceFromPostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseInterestCodeFromPostingProfile name="UseInterestCodeFromPostingProfile">UseInterestCodeFromPostingProfile</a>

First included in: AccountsReceivable/CustBillingClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseInterestCodeFromPostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterestCode name="InterestCode">InterestCode</a>

First included in: AccountsReceivable/CustBillingClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CustBillingClassificationRelationshipId name="BackingTable_CustBillingClassificationRelationshipId">BackingTable_CustBillingClassificationRelationshipId</a>

First included in: AccountsReceivable/CustBillingClassificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CustBillingClassificationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsReceivable/Group/CustBillingClassification.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Group/CustBillingClassification.cdm.json/CustBillingClassification</a></td><td><a href="../../../Tables/Finance/AccountsReceivable/Group/CustBillingClassification.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/CustBillingClassificationEntity (this entity)  

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
