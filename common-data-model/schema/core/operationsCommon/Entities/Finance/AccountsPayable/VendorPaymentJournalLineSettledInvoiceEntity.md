---
title: VendorPaymentJournalLineSettledInvoiceEntity in AccountsPayable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Vendor payment journal line settled invoice in AccountsPayable(VendorPaymentJournalLineSettledInvoiceEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor payment journal line settled invoice</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SettlementAmountInInvoiceCurrency](#SettlementAmountInInvoiceCurrency)||<a href="VendorPaymentJournalLineSettledInvoiceEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity</a>|
|[CashDiscountToTakeInInvoiceCurrency](#CashDiscountToTakeInInvoiceCurrency)||<a href="VendorPaymentJournalLineSettledInvoiceEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity</a>|
|[InvoiceToPaymentCrossRate](#InvoiceToPaymentCrossRate)||<a href="VendorPaymentJournalLineSettledInvoiceEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity</a>|
|[JournalLineCompany](#JournalLineCompany)||<a href="VendorPaymentJournalLineSettledInvoiceEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity</a>|
|[JournalBatchNumber](#JournalBatchNumber)||<a href="VendorPaymentJournalLineSettledInvoiceEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity</a>|
|[JournalLineAccountType](#JournalLineAccountType)||<a href="VendorPaymentJournalLineSettledInvoiceEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity</a>|
|[JournalLineNumber](#JournalLineNumber)||<a href="VendorPaymentJournalLineSettledInvoiceEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity</a>|
|[InvoiceNumber](#InvoiceNumber)||<a href="VendorPaymentJournalLineSettledInvoiceEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity</a>|
|[InvoiceCompany](#InvoiceCompany)||<a href="VendorPaymentJournalLineSettledInvoiceEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity</a>|
|[InvoiceDueDate](#InvoiceDueDate)||<a href="VendorPaymentJournalLineSettledInvoiceEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity</a>|
|[Account](#Account)||<a href="VendorPaymentJournalLineSettledInvoiceEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity</a>|
|[AccountDisplayValue](#AccountDisplayValue)||<a href="VendorPaymentJournalLineSettledInvoiceEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity</a>|
|[invoiceAccount](#invoiceAccount)||<a href="VendorPaymentJournalLineSettledInvoiceEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity</a>|
|[Relationship_VendorPaymentJournalHeaderRelationshipId](#Relationship_VendorPaymentJournalHeaderRelationshipId)||<a href="VendorPaymentJournalLineSettledInvoiceEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity</a>|
|[Relationship_VendorPaymentJournalLineRelationshipId](#Relationship_VendorPaymentJournalLineRelationshipId)||<a href="VendorPaymentJournalLineSettledInvoiceEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity</a>|
|[Relationship_AccountCombinationRelationshipId](#Relationship_AccountCombinationRelationshipId)||<a href="VendorPaymentJournalLineSettledInvoiceEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity</a>|
|[BackingTable_SpecTransRelationshipId](#BackingTable_SpecTransRelationshipId)||<a href="VendorPaymentJournalLineSettledInvoiceEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity</a>|

### <a href=#SettlementAmountInInvoiceCurrency name="SettlementAmountInInvoiceCurrency">SettlementAmountInInvoiceCurrency</a>

First included in: AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementAmountInInvoiceCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountToTakeInInvoiceCurrency name="CashDiscountToTakeInInvoiceCurrency">CashDiscountToTakeInInvoiceCurrency</a>

First included in: AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountToTakeInInvoiceCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceToPaymentCrossRate name="InvoiceToPaymentCrossRate">InvoiceToPaymentCrossRate</a>

First included in: AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceToPaymentCrossRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalLineCompany name="JournalLineCompany">JournalLineCompany</a>

First included in: AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Journal company</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalLineCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Journal company</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalBatchNumber name="JournalBatchNumber">JournalBatchNumber</a>

First included in: AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalLineAccountType name="JournalLineAccountType">JournalLineAccountType</a>

First included in: AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalLineAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalLineNumber name="JournalLineNumber">JournalLineNumber</a>

First included in: AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceNumber name="InvoiceNumber">InvoiceNumber</a>

First included in: AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceCompany name="InvoiceCompany">InvoiceCompany</a>

First included in: AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice company</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice company</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDueDate name="InvoiceDueDate">InvoiceDueDate</a>

First included in: AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Account name="Account">Account</a>

First included in: AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Account attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountDisplayValue name="AccountDisplayValue">AccountDisplayValue</a>

First included in: AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#invoiceAccount name="invoiceAccount">invoiceAccount</a>

First included in: AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the invoiceAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendorPaymentJournalHeaderRelationshipId name="Relationship_VendorPaymentJournalHeaderRelationshipId">Relationship_VendorPaymentJournalHeaderRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendorPaymentJournalHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_VendorPaymentJournalLineRelationshipId name="Relationship_VendorPaymentJournalLineRelationshipId">Relationship_VendorPaymentJournalLineRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendorPaymentJournalLineRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AccountCombinationRelationshipId name="Relationship_AccountCombinationRelationshipId">Relationship_AccountCombinationRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_SpecTransRelationshipId name="BackingTable_SpecTransRelationshipId">BackingTable_SpecTransRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalLineSettledInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SpecTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/WorksheetLine/SpecTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/WorksheetLine/SpecTrans.cdm.json/SpecTrans</a></td><td><a href="../../../Tables/Finance/Bank/WorksheetLine/SpecTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
