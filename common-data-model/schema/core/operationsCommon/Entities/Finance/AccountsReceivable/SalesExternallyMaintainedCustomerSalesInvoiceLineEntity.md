---
title: SalesExternallyMaintainedCustomerSalesInvoiceLineEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Externally maintained customer sales invoice lines in AccountsReceivable(SalesExternallyMaintainedCustomerSalesInvoiceLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Externally maintained customer sales invoice lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ConfirmedShippingDate](#ConfirmedShippingDate)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity</a>|
|[InvoiceDate](#InvoiceDate)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity</a>|
|[InvoicedQuantity](#InvoicedQuantity)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity</a>|
|[InvoiceNumber](#InvoiceNumber)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity</a>|
|[LineAmount](#LineAmount)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity</a>|
|[LineCreationSequenceNumber](#LineCreationSequenceNumber)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity</a>|
|[LineTotalChargeAmount](#LineTotalChargeAmount)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity</a>|
|[LineTotalDiscountAmount](#LineTotalDiscountAmount)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity</a>|
|[LineTotalTaxAmount](#LineTotalTaxAmount)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity</a>|
|[ProductDescription](#ProductDescription)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity</a>|
|[ProductName](#ProductName)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity</a>|
|[ProductNumber](#ProductNumber)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity</a>|
|[SalesPrice](#SalesPrice)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity</a>|
|[SalesUnitSymbol](#SalesUnitSymbol)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity</a>|
|[LedgerVoucher](#LedgerVoucher)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity</a>|
|[BackingTable_SalesInvoiceLineV2EntityRelationshipId](#BackingTable_SalesInvoiceLineV2EntityRelationshipId)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceLineEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity</a>|

### <a href=#ConfirmedShippingDate name="ConfirmedShippingDate">ConfirmedShippingDate</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmedShippingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDate name="InvoiceDate">InvoiceDate</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity (this entity)  

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

### <a href=#InvoicedQuantity name="InvoicedQuantity">InvoicedQuantity</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoicedQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceNumber name="InvoiceNumber">InvoiceNumber</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity (this entity)  

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

### <a href=#LineAmount name="LineAmount">LineAmount</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineCreationSequenceNumber name="LineCreationSequenceNumber">LineCreationSequenceNumber</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineCreationSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineTotalChargeAmount name="LineTotalChargeAmount">LineTotalChargeAmount</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineTotalChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineTotalDiscountAmount name="LineTotalDiscountAmount">LineTotalDiscountAmount</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineTotalDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineTotalTaxAmount name="LineTotalTaxAmount">LineTotalTaxAmount</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineTotalTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductDescription name="ProductDescription">ProductDescription</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductName name="ProductName">ProductName</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductNumber name="ProductNumber">ProductNumber</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPrice name="SalesPrice">SalesPrice</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUnitSymbol name="SalesUnitSymbol">SalesUnitSymbol</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerVoucher name="LedgerVoucher">LedgerVoucher</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_SalesInvoiceLineV2EntityRelationshipId name="BackingTable_SalesInvoiceLineV2EntityRelationshipId">BackingTable_SalesInvoiceLineV2EntityRelationshipId</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SalesInvoiceLineV2EntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceLineEntity (this entity)  

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
