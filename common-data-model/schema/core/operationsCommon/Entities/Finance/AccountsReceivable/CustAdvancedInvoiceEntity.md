---
title: CustAdvancedInvoiceEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# CustAdvancedInvoiceEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/CustAdvancedInvoiceEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CustomerAccount](#CustomerAccount)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[InvoiceAccount](#InvoiceAccount)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[OneTimeCustomer](#OneTimeCustomer)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[PostVAT](#PostVAT)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[PostVATUntil](#PostVATUntil)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[CreateTaxDocument](#CreateTaxDocument)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[PrepaymentPostingProfile](#PrepaymentPostingProfile)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[Status](#Status)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[SalesOrder](#SalesOrder)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[Recipient](#Recipient)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[Language](#Language)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[NumberSequenceGroup](#NumberSequenceGroup)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[Posted](#Posted)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[AdvanceInvoice](#AdvanceInvoice)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[AdvanceInvoiceVoucher](#AdvanceInvoiceVoucher)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[PostingProfile](#PostingProfile)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[WorkerSalesTaker](#WorkerSalesTaker)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[InvoiceAmount](#InvoiceAmount)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[Currency](#Currency)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[Triangulation](#Triangulation)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[InvoiceDate](#InvoiceDate)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DueDate](#DueDate)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DocumentDate](#DocumentDate)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[VATRegisterDate](#VATRegisterDate)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[SalesDocumentStatus](#SalesDocumentStatus)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[FiscalDocumentDate](#FiscalDocumentDate)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[FiscalPrinter](#FiscalPrinter)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[FiscalInvoiceAccount](#FiscalInvoiceAccount)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[FiscalOrderAccount](#FiscalOrderAccount)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[Name](#Name)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[TermsOfPayment](#TermsOfPayment)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[MethodOfPayment](#MethodOfPayment)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[PaymentSpecification](#PaymentSpecification)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[PaymentSchedule](#PaymentSchedule)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[ConstantSymbol](#ConstantSymbol)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[Listcode](#Listcode)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[CountryRegion](#CountryRegion)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[ExchangeRate](#ExchangeRate)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[SecondaryExchangeRate](#SecondaryExchangeRate)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[CustAdvanceInvoiceId](#CustAdvanceInvoiceId)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[HeadId](#HeadId)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[AmountCur](#AmountCur)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[Description](#Description)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[InvoiceTxt](#InvoiceTxt)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[LineNum](#LineNum)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[OffsetLedgerDimension](#OffsetLedgerDimension)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[TaxGroup](#TaxGroup)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[TaxItemGroup](#TaxItemGroup)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[ParentRecId](#ParentRecId)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[CorrectionDescription](#CorrectionDescription)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[OffsetLedgerDimensionDisplayValue](#OffsetLedgerDimensionDisplayValue)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryBuildingCompliment](#DeliveryBuildingCompliment)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryCity](#DeliveryCity)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryCountryRegionId](#DeliveryCountryRegionId)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryCountryRegionISOCode](#DeliveryCountryRegionISOCode)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryCounty](#DeliveryCounty)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryDistrictName](#DeliveryDistrictName)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryDunsNumber](#DeliveryDunsNumber)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryIsPrivate](#DeliveryIsPrivate)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryLatitude](#DeliveryLatitude)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryLocationId](#DeliveryLocationId)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryLongitude](#DeliveryLongitude)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryPostBox](#DeliveryPostBox)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryState](#DeliveryState)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryStreet](#DeliveryStreet)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryStreetNumber](#DeliveryStreetNumber)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryTimeZone](#DeliveryTimeZone)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryValidFrom](#DeliveryValidFrom)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryValidTo](#DeliveryValidTo)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryAddress](#DeliveryAddress)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryZipCode](#DeliveryZipCode)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[ContactPersonId](#ContactPersonId)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[PostalAddress](#PostalAddress)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[DeliveryDescription](#DeliveryDescription)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[CustGroup](#CustGroup)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[ComputedLineNum](#ComputedLineNum)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[RetailOrderReferenceId](#RetailOrderReferenceId)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[RetailStoreId](#RetailStoreId)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[RetailTerminalId](#RetailTerminalId)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[RetailTransactionId](#RetailTransactionId)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[BackingTable_CzCustAdvanceInvoiceTableRelationshipId](#BackingTable_CzCustAdvanceInvoiceTableRelationshipId)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CustAdvancedInvoiceEntity.md" target="_blank">AccountsReceivable/CustAdvancedInvoiceEntity</a>|

### <a href=#CustomerAccount name="CustomerAccount">CustomerAccount</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAccount name="InvoiceAccount">InvoiceAccount</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

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

### <a href=#OneTimeCustomer name="OneTimeCustomer">OneTimeCustomer</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OneTimeCustomer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostVAT name="PostVAT">PostVAT</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostVAT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostVATUntil name="PostVATUntil">PostVATUntil</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostVATUntil attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreateTaxDocument name="CreateTaxDocument">CreateTaxDocument</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateTaxDocument attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrepaymentPostingProfile name="PrepaymentPostingProfile">PrepaymentPostingProfile</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaymentPostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrder name="SalesOrder">SalesOrder</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Recipient name="Recipient">Recipient</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Recipient attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Language name="Language">Language</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Language attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceGroup name="NumberSequenceGroup">NumberSequenceGroup</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Posted name="Posted">Posted</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Posted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdvanceInvoice name="AdvanceInvoice">AdvanceInvoice</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvanceInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdvanceInvoiceVoucher name="AdvanceInvoiceVoucher">AdvanceInvoiceVoucher</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvanceInvoiceVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostingProfile name="PostingProfile">PostingProfile</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerSalesTaker name="WorkerSalesTaker">WorkerSalesTaker</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerSalesTaker attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAmount name="InvoiceAmount">InvoiceAmount</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Triangulation name="Triangulation">Triangulation</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Triangulation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDate name="InvoiceDate">InvoiceDate</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DueDate name="DueDate">DueDate</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATRegisterDate name="VATRegisterDate">VATRegisterDate</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATRegisterDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesDocumentStatus name="SalesDocumentStatus">SalesDocumentStatus</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesDocumentStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalDocumentDate name="FiscalDocumentDate">FiscalDocumentDate</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalPrinter name="FiscalPrinter">FiscalPrinter</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalPrinter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalInvoiceAccount name="FiscalInvoiceAccount">FiscalInvoiceAccount</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalInvoiceAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalOrderAccount name="FiscalOrderAccount">FiscalOrderAccount</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalOrderAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TermsOfPayment name="TermsOfPayment">TermsOfPayment</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

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

### <a href=#MethodOfPayment name="MethodOfPayment">MethodOfPayment</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MethodOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentSpecification name="PaymentSpecification">PaymentSpecification</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSpecification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentSchedule name="PaymentSchedule">PaymentSchedule</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSchedule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConstantSymbol name="ConstantSymbol">ConstantSymbol</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConstantSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Listcode name="Listcode">Listcode</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Listcode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountryRegion name="CountryRegion">CountryRegion</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRate name="ExchangeRate">ExchangeRate</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondaryExchangeRate name="SecondaryExchangeRate">SecondaryExchangeRate</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondaryExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustAdvanceInvoiceId name="CustAdvanceInvoiceId">CustAdvanceInvoiceId</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAdvanceInvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeadId name="HeadId">HeadId</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeadId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountCur name="AmountCur">AmountCur</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCur attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

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

### <a href=#InvoiceTxt name="InvoiceTxt">InvoiceTxt</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceTxt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetLedgerDimension name="OffsetLedgerDimension">OffsetLedgerDimension</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroup name="TaxGroup">TaxGroup</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxItemGroup name="TaxItemGroup">TaxItemGroup</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxItemGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentRecId name="ParentRecId">ParentRecId</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionDescription name="CorrectionDescription">CorrectionDescription</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetLedgerDimensionDisplayValue name="OffsetLedgerDimensionDisplayValue">OffsetLedgerDimensionDisplayValue</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryBuildingCompliment name="DeliveryBuildingCompliment">DeliveryBuildingCompliment</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryCity name="DeliveryCity">DeliveryCity</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryCountryRegionId name="DeliveryCountryRegionId">DeliveryCountryRegionId</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryCountryRegionISOCode name="DeliveryCountryRegionISOCode">DeliveryCountryRegionISOCode</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryCounty name="DeliveryCounty">DeliveryCounty</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryCounty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryDistrictName name="DeliveryDistrictName">DeliveryDistrictName</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryDunsNumber name="DeliveryDunsNumber">DeliveryDunsNumber</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDunsNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryIsPrivate name="DeliveryIsPrivate">DeliveryIsPrivate</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryIsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryLatitude name="DeliveryLatitude">DeliveryLatitude</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryLocationId name="DeliveryLocationId">DeliveryLocationId</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryLongitude name="DeliveryLongitude">DeliveryLongitude</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryPostBox name="DeliveryPostBox">DeliveryPostBox</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryState name="DeliveryState">DeliveryState</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryStreet name="DeliveryStreet">DeliveryStreet</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryStreetNumber name="DeliveryStreetNumber">DeliveryStreetNumber</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTimeZone name="DeliveryTimeZone">DeliveryTimeZone</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryValidFrom name="DeliveryValidFrom">DeliveryValidFrom</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryValidTo name="DeliveryValidTo">DeliveryValidTo</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddress name="DeliveryAddress">DeliveryAddress</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryZipCode name="DeliveryZipCode">DeliveryZipCode</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonId name="ContactPersonId">ContactPersonId</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostalAddress name="PostalAddress">PostalAddress</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostalAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryDescription name="DeliveryDescription">DeliveryDescription</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustGroup name="CustGroup">CustGroup</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ComputedLineNum name="ComputedLineNum">ComputedLineNum</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ComputedLineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailOrderReferenceId name="RetailOrderReferenceId">RetailOrderReferenceId</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailOrderReferenceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailStoreId name="RetailStoreId">RetailStoreId</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailStoreId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailTerminalId name="RetailTerminalId">RetailTerminalId</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailTerminalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailTransactionId name="RetailTransactionId">RetailTransactionId</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailTransactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CzCustAdvanceInvoiceTableRelationshipId name="BackingTable_CzCustAdvanceInvoiceTableRelationshipId">BackingTable_CzCustAdvanceInvoiceTableRelationshipId</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CzCustAdvanceInvoiceTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsPayable/WorksheetHeader/CzCustAdvanceInvoiceTable.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/WorksheetHeader/CzCustAdvanceInvoiceTable.cdm.json/CzCustAdvanceInvoiceTable</a></td><td><a href="../../../Tables/Finance/AccountsPayable/WorksheetHeader/CzCustAdvanceInvoiceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/CustAdvancedInvoiceEntity (this entity)  

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
