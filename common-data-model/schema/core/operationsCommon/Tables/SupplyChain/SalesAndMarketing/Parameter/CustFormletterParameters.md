---
title: CustFormletterParameters in Parameter - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Customer, form parameters in Parameter(CustFormletterParameters)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Parameter/CustFormletterParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustFormletterParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer, form parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[BlankItemId](#BlankItemId)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[CreditNotePrintType_RU](#CreditNotePrintType_RU)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[ExternalItemOverwriteAppend](#ExternalItemOverwriteAppend)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[GiroOnAccountStatement](#GiroOnAccountStatement)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[GiroOnCollectionletter](#GiroOnCollectionletter)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[GiroOnFreeTextInvoice](#GiroOnFreeTextInvoice)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[GiroOnInterest](#GiroOnInterest)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[GiroOnInvoice](#GiroOnInvoice)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[InventDimConfirm](#InventDimConfirm)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[InventDimInvoice](#InventDimInvoice)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[InventDimInvoice4Paym_RU](#InventDimInvoice4Paym_RU)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[InventDimPackingSlip](#InventDimPackingSlip)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[InventDimPickingList](#InventDimPickingList)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[InventDimQuotation](#InventDimQuotation)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[InventDimSalesAgreement](#InventDimSalesAgreement)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[ItemDimPlacement](#ItemDimPlacement)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[ItemDimSeparator](#ItemDimSeparator)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[ItemNameAndTxt2Description](#ItemNameAndTxt2Description)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[ItemNum](#ItemNum)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[Key](#Key)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PckSlpInfoOnInvoice](#PckSlpInfoOnInvoice)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrePrintLevelAccountStatement](#PrePrintLevelAccountStatement)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrePrintLevelCollectionLetter](#PrePrintLevelCollectionLetter)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrePrintLevelConfirm](#PrePrintLevelConfirm)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrePrintLevelFreeTextInvoice](#PrePrintLevelFreeTextInvoice)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrePrintLevelInterestNote](#PrePrintLevelInterestNote)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrePrintLevelInvoice](#PrePrintLevelInvoice)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrePrintLevelPackingSlip](#PrePrintLevelPackingSlip)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrePrintLevelQuotation](#PrePrintLevelQuotation)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrePrintLevelSalesAgreement](#PrePrintLevelSalesAgreement)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrintAgreementClassification](#PrintAgreementClassification)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrintCashDiscount](#PrintCashDiscount)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrintContractReference](#PrintContractReference)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrintCustAccountStatementVATNum](#PrintCustAccountStatementVATNum)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrintDeliveryTerm](#PrintDeliveryTerm)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrintEuroAmount](#PrintEuroAmount)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrintFreeTextInvoiceVATNum](#PrintFreeTextInvoiceVATNum)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrintFTICreditNoteLines_PL](#PrintFTICreditNoteLines_PL)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrintInterestNoteVATNum](#PrintInterestNoteVATNum)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrintInvoiceCreditNoteLines_PL](#PrintInvoiceCreditNoteLines_PL)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrintInvoiceVATNum](#PrintInvoiceVATNum)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrintMaxIsEnforced](#PrintMaxIsEnforced)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrintModeOfDelivery](#PrintModeOfDelivery)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrintPayment](#PrintPayment)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[ShippingDetailsOnPackingSlip](#ShippingDetailsOnPackingSlip)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[ShowOnlyOneShippingLineOnPackingSlip](#ShowOnlyOneShippingLineOnPackingSlip)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[StoreInPrintArchivePackingSlip](#StoreInPrintArchivePackingSlip)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[TaxPrintTaxFreeBalance](#TaxPrintTaxFreeBalance)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[TaxSpecPrintLevel](#TaxSpecPrintLevel)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[TotalsFirstLastPage](#TotalsFirstLastPage)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[TrackBackorderInvoice](#TrackBackorderInvoice)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[TrackBackorderPackingSlip](#TrackBackorderPackingSlip)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[TransportationDocumentOnPackingSlip](#TransportationDocumentOnPackingSlip)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrintConfirmationVATNum](#PrintConfirmationVATNum)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrintQuotationVATNum](#PrintQuotationVATNum)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrintSalesAgreementVATNum](#PrintSalesAgreementVATNum)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[PrintSalesPackingSlipVATNum](#PrintSalesPackingSlipVATNum)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[AttachFreeNotesDirectly_IT](#AttachFreeNotesDirectly_IT)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[DataAreaId](#DataAreaId)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[Relationship_BlankInventTableRelationshipId](#Relationship_BlankInventTableRelationshipId)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="CustFormletterParameters.md" target="_blank">Parameter/CustFormletterParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustFormletterParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BlankItemId name="BlankItemId">BlankItemId</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BlankItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditNotePrintType_RU name="CreditNotePrintType_RU">CreditNotePrintType_RU</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditNotePrintType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ExternalItemOverwriteAppend name="ExternalItemOverwriteAppend">ExternalItemOverwriteAppend</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalItemOverwriteAppend attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#GiroOnAccountStatement name="GiroOnAccountStatement">GiroOnAccountStatement</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroOnAccountStatement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#GiroOnCollectionletter name="GiroOnCollectionletter">GiroOnCollectionletter</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroOnCollectionletter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#GiroOnFreeTextInvoice name="GiroOnFreeTextInvoice">GiroOnFreeTextInvoice</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Associated payment attachment on free text invoice</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroOnFreeTextInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Associated payment attachment on free text invoice</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#GiroOnInterest name="GiroOnInterest">GiroOnInterest</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroOnInterest attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#GiroOnInvoice name="GiroOnInvoice">GiroOnInvoice</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiroOnInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventDimConfirm name="InventDimConfirm">InventDimConfirm</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimConfirm attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventDimInvoice name="InventDimInvoice">InventDimInvoice</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventDimInvoice4Paym_RU name="InventDimInvoice4Paym_RU">InventDimInvoice4Paym_RU</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimInvoice4Paym_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventDimPackingSlip name="InventDimPackingSlip">InventDimPackingSlip</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimPackingSlip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventDimPickingList name="InventDimPickingList">InventDimPickingList</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimPickingList attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventDimQuotation name="InventDimQuotation">InventDimQuotation</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimQuotation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventDimSalesAgreement name="InventDimSalesAgreement">InventDimSalesAgreement</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimSalesAgreement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ItemDimPlacement name="ItemDimPlacement">ItemDimPlacement</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemDimPlacement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ItemDimSeparator name="ItemDimSeparator">ItemDimSeparator</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product dimension separator</td></tr><tr><td>dataFormat</td><td>char</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemDimSeparator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product dimension separator</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#ItemNameAndTxt2Description name="ItemNameAndTxt2Description">ItemNameAndTxt2Description</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNameAndTxt2Description attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ItemNum name="ItemNum">ItemNum</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PckSlpInfoOnInvoice name="PckSlpInfoOnInvoice">PckSlpInfoOnInvoice</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PckSlpInfoOnInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrePrintLevelAccountStatement name="PrePrintLevelAccountStatement">PrePrintLevelAccountStatement</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Paper format</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePrintLevelAccountStatement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Paper format</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PrePrintLevelCollectionLetter name="PrePrintLevelCollectionLetter">PrePrintLevelCollectionLetter</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Paper format</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePrintLevelCollectionLetter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Paper format</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PrePrintLevelConfirm name="PrePrintLevelConfirm">PrePrintLevelConfirm</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Paper format</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePrintLevelConfirm attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Paper format</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PrePrintLevelFreeTextInvoice name="PrePrintLevelFreeTextInvoice">PrePrintLevelFreeTextInvoice</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Paper format</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePrintLevelFreeTextInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Paper format</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PrePrintLevelInterestNote name="PrePrintLevelInterestNote">PrePrintLevelInterestNote</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Paper format</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePrintLevelInterestNote attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Paper format</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PrePrintLevelInvoice name="PrePrintLevelInvoice">PrePrintLevelInvoice</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Paper format</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePrintLevelInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Paper format</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PrePrintLevelPackingSlip name="PrePrintLevelPackingSlip">PrePrintLevelPackingSlip</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Paper format</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePrintLevelPackingSlip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Paper format</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PrePrintLevelQuotation name="PrePrintLevelQuotation">PrePrintLevelQuotation</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Paper format</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePrintLevelQuotation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Paper format</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PrePrintLevelSalesAgreement name="PrePrintLevelSalesAgreement">PrePrintLevelSalesAgreement</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Paper format</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePrintLevelSalesAgreement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Paper format</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PrintAgreementClassification name="PrintAgreementClassification">PrintAgreementClassification</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintAgreementClassification attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintCashDiscount name="PrintCashDiscount">PrintCashDiscount</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintCashDiscount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintContractReference name="PrintContractReference">PrintContractReference</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintContractReference attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintCustAccountStatementVATNum name="PrintCustAccountStatementVATNum">PrintCustAccountStatementVATNum</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintCustAccountStatementVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintDeliveryTerm name="PrintDeliveryTerm">PrintDeliveryTerm</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintDeliveryTerm attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintEuroAmount name="PrintEuroAmount">PrintEuroAmount</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintEuroAmount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintFreeTextInvoiceVATNum name="PrintFreeTextInvoiceVATNum">PrintFreeTextInvoiceVATNum</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintFreeTextInvoiceVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintFTICreditNoteLines_PL name="PrintFTICreditNoteLines_PL">PrintFTICreditNoteLines_PL</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintFTICreditNoteLines_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintInterestNoteVATNum name="PrintInterestNoteVATNum">PrintInterestNoteVATNum</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintInterestNoteVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintInvoiceCreditNoteLines_PL name="PrintInvoiceCreditNoteLines_PL">PrintInvoiceCreditNoteLines_PL</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintInvoiceCreditNoteLines_PL attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintInvoiceVATNum name="PrintInvoiceVATNum">PrintInvoiceVATNum</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintInvoiceVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintMaxIsEnforced name="PrintMaxIsEnforced">PrintMaxIsEnforced</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintMaxIsEnforced attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintModeOfDelivery name="PrintModeOfDelivery">PrintModeOfDelivery</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintModeOfDelivery attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintPayment name="PrintPayment">PrintPayment</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintPayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShippingDetailsOnPackingSlip name="ShippingDetailsOnPackingSlip">ShippingDetailsOnPackingSlip</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping details</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingDetailsOnPackingSlip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping details</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ShowOnlyOneShippingLineOnPackingSlip name="ShowOnlyOneShippingLineOnPackingSlip">ShowOnlyOneShippingLineOnPackingSlip</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Only one shipping line</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowOnlyOneShippingLineOnPackingSlip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Only one shipping line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#StoreInPrintArchivePackingSlip name="StoreInPrintArchivePackingSlip">StoreInPrintArchivePackingSlip</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreInPrintArchivePackingSlip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxPrintTaxFreeBalance name="TaxPrintTaxFreeBalance">TaxPrintTaxFreeBalance</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPrintTaxFreeBalance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxSpecPrintLevel name="TaxSpecPrintLevel">TaxSpecPrintLevel</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSpecPrintLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TotalsFirstLastPage name="TotalsFirstLastPage">TotalsFirstLastPage</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Totals</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalsFirstLastPage attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Totals</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TrackBackorderInvoice name="TrackBackorderInvoice">TrackBackorderInvoice</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackBackorderInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TrackBackorderPackingSlip name="TrackBackorderPackingSlip">TrackBackorderPackingSlip</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackBackorderPackingSlip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TransportationDocumentOnPackingSlip name="TransportationDocumentOnPackingSlip">TransportationDocumentOnPackingSlip</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transportation document</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationDocumentOnPackingSlip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transportation document</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PrintConfirmationVATNum name="PrintConfirmationVATNum">PrintConfirmationVATNum</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintConfirmationVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintQuotationVATNum name="PrintQuotationVATNum">PrintQuotationVATNum</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintQuotationVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintSalesAgreementVATNum name="PrintSalesAgreementVATNum">PrintSalesAgreementVATNum</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintSalesAgreementVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintSalesPackingSlipVATNum name="PrintSalesPackingSlipVATNum">PrintSalesPackingSlipVATNum</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintSalesPackingSlipVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AttachFreeNotesDirectly_IT name="AttachFreeNotesDirectly_IT">AttachFreeNotesDirectly_IT</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Direct attachment to documents</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttachFreeNotesDirectly_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Direct attachment to documents</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/CustFormletterParameters (this entity)  

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

### <a href=#Relationship_BlankInventTableRelationshipId name="Relationship_BlankInventTableRelationshipId">Relationship_BlankInventTableRelationshipId</a>

First included in: Parameter/CustFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BlankInventTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/CustFormletterParameters (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
