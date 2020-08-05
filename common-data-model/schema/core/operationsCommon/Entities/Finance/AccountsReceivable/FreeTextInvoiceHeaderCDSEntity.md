---
title: FreeTextInvoiceHeaderCDSEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# CDS customer free text invoice headers in AccountsReceivable(FreeTextInvoiceHeaderCDSEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/FreeTextInvoiceHeaderCDSEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CDS customer free text invoice headers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ExternalInvoiceId](#ExternalInvoiceId)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[CashDiscountCode](#CashDiscountCode)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[CashDiscountDate](#CashDiscountDate)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[ComplimentedInvoiceId](#ComplimentedInvoiceId)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[ContactPersonId](#ContactPersonId)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[CustomerAccount](#CustomerAccount)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[CustomerGroup](#CustomerGroup)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[CustomerReference](#CustomerReference)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[CustomerRequisition](#CustomerRequisition)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[DocumentDate](#DocumentDate)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[DueDate](#DueDate)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[FreeTextNumber](#FreeTextNumber)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[GiroType](#GiroType)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[InclTax](#InclTax)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[InvoiceAccount](#InvoiceAccount)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[InvoiceDate](#InvoiceDate)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[InvoiceId](#InvoiceId)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[InvoiceName](#InvoiceName)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[InvoiceOriginType](#InvoiceOriginType)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[IsPosted](#IsPosted)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[IsPostedViaIntercompany](#IsPostedViaIntercompany)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[LanguageId](#LanguageId)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[MethodOfPayment](#MethodOfPayment)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[PaymentSchedule](#PaymentSchedule)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[PaymentTermsBaseDate](#PaymentTermsBaseDate)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[PaymentTermsBaseDays](#PaymentTermsBaseDays)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[SalesTaxGroupId](#SalesTaxGroupId)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[SalesTaxItemGroupId](#SalesTaxItemGroupId)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[TermsOfPayment](#TermsOfPayment)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[Relationship_OrderingCustomerRelationshipId](#Relationship_OrderingCustomerRelationshipId)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[Relationship_InvoicingCustomerRelationshipId](#Relationship_InvoicingCustomerRelationshipId)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[Relationship_PaymentTermsRelationshipId](#Relationship_PaymentTermsRelationshipId)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[Relationship_CashDiscountRelationshipId](#Relationship_CashDiscountRelationshipId)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[Relationship_PaymentScheduleRelationshipId](#Relationship_PaymentScheduleRelationshipId)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[Relationship_PaymentMethodRelationshipId](#Relationship_PaymentMethodRelationshipId)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[BackingTable_FreeTextInvoiceHeaderEntityRelationshipId](#BackingTable_FreeTextInvoiceHeaderEntityRelationshipId)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="FreeTextInvoiceHeaderCDSEntity.md" target="_blank">AccountsReceivable/FreeTextInvoiceHeaderCDSEntity</a>|

### <a href=#ExternalInvoiceId name="ExternalInvoiceId">ExternalInvoiceId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalInvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountCode name="CashDiscountCode">CashDiscountCode</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountDate name="CashDiscountDate">CashDiscountDate</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComplimentedInvoiceId name="ComplimentedInvoiceId">ComplimentedInvoiceId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComplimentedInvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonId name="ContactPersonId">ContactPersonId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

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

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

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

### <a href=#CustomerAccount name="CustomerAccount">CustomerAccount</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerGroup name="CustomerGroup">CustomerGroup</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerReference name="CustomerReference">CustomerReference</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerRequisition name="CustomerRequisition">CustomerRequisition</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerRequisition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DueDate name="DueDate">DueDate</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreeTextNumber name="FreeTextNumber">FreeTextNumber</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreeTextNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiroType name="GiroType">GiroType</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InclTax name="InclTax">InclTax</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InclTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAccount name="InvoiceAccount">InvoiceAccount</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDate name="InvoiceDate">InvoiceDate</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

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

### <a href=#InvoiceId name="InvoiceId">InvoiceId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceName name="InvoiceName">InvoiceName</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceOriginType name="InvoiceOriginType">InvoiceOriginType</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceOriginType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPosted name="IsPosted">IsPosted</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPosted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPostedViaIntercompany name="IsPostedViaIntercompany">IsPostedViaIntercompany</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPostedViaIntercompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MethodOfPayment name="MethodOfPayment">MethodOfPayment</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MethodOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentSchedule name="PaymentSchedule">PaymentSchedule</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSchedule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTermsBaseDate name="PaymentTermsBaseDate">PaymentTermsBaseDate</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTermsBaseDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTermsBaseDays name="PaymentTermsBaseDays">PaymentTermsBaseDays</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTermsBaseDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroupId name="SalesTaxGroupId">SalesTaxGroupId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxItemGroupId name="SalesTaxItemGroupId">SalesTaxItemGroupId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxItemGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TermsOfPayment name="TermsOfPayment">TermsOfPayment</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TermsOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OrderingCustomerRelationshipId name="Relationship_OrderingCustomerRelationshipId">Relationship_OrderingCustomerRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OrderingCustomerRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_InvoicingCustomerRelationshipId name="Relationship_InvoicingCustomerRelationshipId">Relationship_InvoicingCustomerRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InvoicingCustomerRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PaymentTermsRelationshipId name="Relationship_PaymentTermsRelationshipId">Relationship_PaymentTermsRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentTermsRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CashDiscountRelationshipId name="Relationship_CashDiscountRelationshipId">Relationship_CashDiscountRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CashDiscountRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PaymentScheduleRelationshipId name="Relationship_PaymentScheduleRelationshipId">Relationship_PaymentScheduleRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentScheduleRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PaymentMethodRelationshipId name="Relationship_PaymentMethodRelationshipId">Relationship_PaymentMethodRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentMethodRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_FreeTextInvoiceHeaderEntityRelationshipId name="BackingTable_FreeTextInvoiceHeaderEntityRelationshipId">BackingTable_FreeTextInvoiceHeaderEntityRelationshipId</a>

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_FreeTextInvoiceHeaderEntityRelationshipId attribute are listed below.</summary>

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

First included in: AccountsReceivable/FreeTextInvoiceHeaderCDSEntity (this entity)  

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
