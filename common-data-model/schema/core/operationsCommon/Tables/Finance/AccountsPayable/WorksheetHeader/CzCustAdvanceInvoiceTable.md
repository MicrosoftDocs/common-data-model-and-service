---
title: CzCustAdvanceInvoiceTable in WorksheetHeader - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Advance invoice in WorksheetHeader(CzCustAdvanceInvoiceTable)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsPayable/WorksheetHeader/CzCustAdvanceInvoiceTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CzCustAdvanceInvoiceTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advance invoice</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[FiscalOrderAccount_PL](#FiscalOrderAccount_PL)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[BankConstantSymbol](#BankConstantSymbol)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[ContactPersonId](#ContactPersonId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[CurrencyCode](#CurrencyCode)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[CustGroup](#CustGroup)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[CustPostingProfile](#CustPostingProfile)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[DefaultDimension](#DefaultDimension)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[DocumentDate](#DocumentDate)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[DueDate](#DueDate)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[ExchRate](#ExchRate)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[ExchrateSecond](#ExchrateSecond)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[FiscalDocDate_PL](#FiscalDocDate_PL)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[FiscalDocState_PL](#FiscalDocState_PL)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[FiscalInvoiceAccount_PL](#FiscalInvoiceAccount_PL)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[FiscalPrinterCode_PL](#FiscalPrinterCode_PL)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[FreeInvoiceRefRecId](#FreeInvoiceRefRecId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[InvoiceAccount](#InvoiceAccount)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[InvoiceAmount](#InvoiceAmount)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[InvoiceDate](#InvoiceDate)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[InvoiceId](#InvoiceId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[LanguageId](#LanguageId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Listcode](#Listcode)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Log](#Log)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Name](#Name)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[NumberSequenceGroup](#NumberSequenceGroup)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[OneTimeCustomer](#OneTimeCustomer)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[OrderAccount](#OrderAccount)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Payment](#Payment)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[PaymentSched](#PaymentSched)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[PaymMode](#PaymMode)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[PaymSpec](#PaymSpec)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[PostalAddress](#PostalAddress)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Posted](#Posted)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[PostingProfile](#PostingProfile)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[PostVAT](#PostVAT)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[PostVATDate](#PostVATDate)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[SalesId](#SalesId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Status](#Status)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[TaxDocumentCreate](#TaxDocumentCreate)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Triangulation](#Triangulation)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Type](#Type)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[VatDueDate_W](#VatDueDate_W)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Voucher](#Voucher)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[WorkerSalesTaker](#WorkerSalesTaker)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[HeadId](#HeadId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[RetailOrderReferenceId](#RetailOrderReferenceId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[RetailStoreId](#RetailStoreId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[RetailTerminalId](#RetailTerminalId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[RetailTransactionId](#RetailTransactionId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[DataAreaId](#DataAreaId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_BankConstantSymbolRelationshipId](#Relationship_BankConstantSymbolRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_ContactPersonRelationshipId](#Relationship_ContactPersonRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_CustGroupRelationshipId](#Relationship_CustGroupRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_CustInvoiceTableRelationshipId](#Relationship_CustInvoiceTableRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_CustLedger_CustPostingProfileRelationshipId](#Relationship_CustLedger_CustPostingProfileRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_CustLedger_PostingProfileRelationshipId](#Relationship_CustLedger_PostingProfileRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_CustPaymModeSpecRelationshipId](#Relationship_CustPaymModeSpecRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_CustPaymModeTableRelationshipId](#Relationship_CustPaymModeTableRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_CustTable_FiscalInvoiceAccount_PLRelationshipId](#Relationship_CustTable_FiscalInvoiceAccount_PLRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_CustTable_FiscalOrderAccount_PLRelationshipId](#Relationship_CustTable_FiscalOrderAccount_PLRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_CustTable_InvoiceAccountRelationshipId](#Relationship_CustTable_InvoiceAccountRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_CustTable_OrderAccountRelationshipId](#Relationship_CustTable_OrderAccountRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_LanguageTableRelationshipId](#Relationship_LanguageTableRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_NumberSequenceGroupRelationshipId](#Relationship_NumberSequenceGroupRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_PaymentSchedRelationshipId](#Relationship_PaymentSchedRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_PaymTermRelationshipId](#Relationship_PaymTermRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_PlFiscalPrinterTableRelationshipId](#Relationship_PlFiscalPrinterTableRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_PostalAddressRelationshipId](#Relationship_PostalAddressRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_SalesParmTableRelationshipId](#Relationship_SalesParmTableRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_SalesTableRelationshipId](#Relationship_SalesTableRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="CzCustAdvanceInvoiceTable.md" target="_blank">WorksheetHeader/CzCustAdvanceInvoiceTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CzCustAdvanceInvoiceTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalOrderAccount_PL name="FiscalOrderAccount_PL">FiscalOrderAccount_PL</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalOrderAccount_PL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankConstantSymbol name="BankConstantSymbol">BankConstantSymbol</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankConstantSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonId name="ContactPersonId">ContactPersonId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

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

### <a href=#CustGroup name="CustGroup">CustGroup</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustPostingProfile name="CustPostingProfile">CustPostingProfile</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustPostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#DueDate name="DueDate">DueDate</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Due</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Due</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#ExchRate name="ExchRate">ExchRate</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExchrateSecond name="ExchrateSecond">ExchrateSecond</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchrateSecond attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FiscalDocDate_PL name="FiscalDocDate_PL">FiscalDocDate_PL</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocDate_PL attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#FiscalDocState_PL name="FiscalDocState_PL">FiscalDocState_PL</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocState_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#FiscalInvoiceAccount_PL name="FiscalInvoiceAccount_PL">FiscalInvoiceAccount_PL</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalInvoiceAccount_PL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalPrinterCode_PL name="FiscalPrinterCode_PL">FiscalPrinterCode_PL</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalPrinterCode_PL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreeInvoiceRefRecId name="FreeInvoiceRefRecId">FreeInvoiceRefRecId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreeInvoiceRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InvoiceAccount name="InvoiceAccount">InvoiceAccount</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAmount name="InvoiceAmount">InvoiceAmount</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InvoiceDate name="InvoiceDate">InvoiceDate</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#InvoiceId name="InvoiceId">InvoiceId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Listcode name="Listcode">Listcode</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Listcode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Log name="Log">Log</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Log attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceGroup name="NumberSequenceGroup">NumberSequenceGroup</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OneTimeCustomer name="OneTimeCustomer">OneTimeCustomer</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OneTimeCustomer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#OrderAccount name="OrderAccount">OrderAccount</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Payment name="Payment">Payment</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Payment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentSched name="PaymentSched">PaymentSched</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSched attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymMode name="PaymMode">PaymMode</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymSpec name="PaymSpec">PaymSpec</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymSpec attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostalAddress name="PostalAddress">PostalAddress</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostalAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Posted name="Posted">Posted</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Posted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PostingProfile name="PostingProfile">PostingProfile</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Posting profile with prepayment journal voucher</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Posting profile with prepayment journal voucher</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostVAT name="PostVAT">PostVAT</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostVAT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PostVATDate name="PostVATDate">PostVATDate</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostVATDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#SalesId name="SalesId">SalesId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxDocumentCreate name="TaxDocumentCreate">TaxDocumentCreate</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxDocumentCreate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Triangulation name="Triangulation">Triangulation</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Triangulation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Type name="Type">Type</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Type attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#VatDueDate_W name="VatDueDate_W">VatDueDate_W</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VatDueDate_W attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#Voucher name="Voucher">Voucher</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Voucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerSalesTaker name="WorkerSalesTaker">WorkerSalesTaker</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recipient</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerSalesTaker attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Recipient</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#HeadId name="HeadId">HeadId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeadId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailOrderReferenceId name="RetailOrderReferenceId">RetailOrderReferenceId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailOrderReferenceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailStoreId name="RetailStoreId">RetailStoreId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailStoreId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailTerminalId name="RetailTerminalId">RetailTerminalId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailTerminalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailTransactionId name="RetailTransactionId">RetailTransactionId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailTransactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

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

### <a href=#Relationship_BankConstantSymbolRelationshipId name="Relationship_BankConstantSymbolRelationshipId">Relationship_BankConstantSymbolRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankConstantSymbolRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Miscellaneous/BankConstantSymbol.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Miscellaneous/BankConstantSymbol.cdm.json/BankConstantSymbol</a></td><td><a href="../../Bank/Miscellaneous/BankConstantSymbol.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ContactPersonRelationshipId name="Relationship_ContactPersonRelationshipId">Relationship_ContactPersonRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ContactPersonRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Main/ContactPerson.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/ContactPerson.cdm.json/ContactPerson</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Main/ContactPerson.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CustGroupRelationshipId name="Relationship_CustGroupRelationshipId">Relationship_CustGroupRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Group/CustGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Group/CustGroup.cdm.json/CustGroup</a></td><td><a href="../../AccountsReceivable/Group/CustGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustInvoiceTableRelationshipId name="Relationship_CustInvoiceTableRelationshipId">Relationship_CustInvoiceTableRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustInvoiceTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/WorksheetHeader/CustInvoiceTable.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/WorksheetHeader/CustInvoiceTable.cdm.json/CustInvoiceTable</a></td><td><a href="../../AccountsReceivable/WorksheetHeader/CustInvoiceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustLedger_CustPostingProfileRelationshipId name="Relationship_CustLedger_CustPostingProfileRelationshipId">Relationship_CustLedger_CustPostingProfileRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustLedger_CustPostingProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Group/CustLedger.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Group/CustLedger.cdm.json/CustLedger</a></td><td><a href="../../AccountsReceivable/Group/CustLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustLedger_PostingProfileRelationshipId name="Relationship_CustLedger_PostingProfileRelationshipId">Relationship_CustLedger_PostingProfileRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustLedger_PostingProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Group/CustLedger.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Group/CustLedger.cdm.json/CustLedger</a></td><td><a href="../../AccountsReceivable/Group/CustLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustPaymModeSpecRelationshipId name="Relationship_CustPaymModeSpecRelationshipId">Relationship_CustPaymModeSpecRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustPaymModeSpecRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Group/CustPaymModeSpec.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/CustPaymModeSpec.cdm.json/CustPaymModeSpec</a></td><td><a href="../../Bank/Group/CustPaymModeSpec.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustPaymModeTableRelationshipId name="Relationship_CustPaymModeTableRelationshipId">Relationship_CustPaymModeTableRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustPaymModeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Group/CustPaymModeTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/CustPaymModeTable.cdm.json/CustPaymModeTable</a></td><td><a href="../../Bank/Group/CustPaymModeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTable_FiscalInvoiceAccount_PLRelationshipId name="Relationship_CustTable_FiscalInvoiceAccount_PLRelationshipId">Relationship_CustTable_FiscalInvoiceAccount_PLRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTable_FiscalInvoiceAccount_PLRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTable_FiscalOrderAccount_PLRelationshipId name="Relationship_CustTable_FiscalOrderAccount_PLRelationshipId">Relationship_CustTable_FiscalOrderAccount_PLRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTable_FiscalOrderAccount_PLRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTable_InvoiceAccountRelationshipId name="Relationship_CustTable_InvoiceAccountRelationshipId">Relationship_CustTable_InvoiceAccountRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTable_InvoiceAccountRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTable_OrderAccountRelationshipId name="Relationship_CustTable_OrderAccountRelationshipId">Relationship_CustTable_OrderAccountRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTable_OrderAccountRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LanguageTableRelationshipId name="Relationship_LanguageTableRelationshipId">Relationship_LanguageTableRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LanguageTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/LanguageTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/LanguageTable.cdm.json/LanguageTable</a></td><td><a href="../../../System/SystemAdministration/Group/LanguageTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_NumberSequenceGroupRelationshipId name="Relationship_NumberSequenceGroupRelationshipId">Relationship_NumberSequenceGroupRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_NumberSequenceGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceGroup.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Framework/NumberSequenceGroup.cdm.json/NumberSequenceGroup</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentSchedRelationshipId name="Relationship_PaymentSchedRelationshipId">Relationship_PaymentSchedRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentSchedRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Group/PaymSched.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/PaymSched.cdm.json/PaymSched</a></td><td><a href="../../Bank/Group/PaymSched.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymTermRelationshipId name="Relationship_PaymTermRelationshipId">Relationship_PaymTermRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymTermRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Group/PaymTerm.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/PaymTerm.cdm.json/PaymTerm</a></td><td><a href="../../Bank/Group/PaymTerm.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PlFiscalPrinterTableRelationshipId name="Relationship_PlFiscalPrinterTableRelationshipId">Relationship_PlFiscalPrinterTableRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PlFiscalPrinterTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../APARShared/Main/PlFiscalPrinterTable.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Main/PlFiscalPrinterTable.cdm.json/PlFiscalPrinterTable</a></td><td><a href="../../APARShared/Main/PlFiscalPrinterTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PostalAddressRelationshipId name="Relationship_PostalAddressRelationshipId">Relationship_PostalAddressRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PostalAddressRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsPostalAddress.cdm.json/LogisticsPostalAddress</a></td><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesParmTableRelationshipId name="Relationship_SalesParmTableRelationshipId">Relationship_SalesParmTableRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesParmTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Transaction/SalesParmTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Transaction/SalesParmTable.cdm.json/SalesParmTable</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Transaction/SalesParmTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesTableRelationshipId name="Relationship_SalesTableRelationshipId">Relationship_SalesTableRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.cdm.json/SalesTable</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/CzCustAdvanceInvoiceTable (this entity)  

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
