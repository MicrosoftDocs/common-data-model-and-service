---
title: VendFormletterParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Vendor, form parameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsPayable/Parameter/VendFormletterParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendFormletterParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor, form parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[CreditNotePrintType_RU](#CreditNotePrintType_RU)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[ExternalItemOverwriteAppend](#ExternalItemOverwriteAppend)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[HighlightUpdatedLines](#HighlightUpdatedLines)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[HighlightUpdatedLinesConfirmationRequest](#HighlightUpdatedLinesConfirmationRequest)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[InventDimInvoice](#InventDimInvoice)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[InventDimPackingSlip](#InventDimPackingSlip)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[InventDimPurchaseAgreement](#InventDimPurchaseAgreement)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[InventDimPurchaseOrder](#InventDimPurchaseOrder)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[InventDimPurchOrderConfirmationRequest](#InventDimPurchOrderConfirmationRequest)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[InventDimPurchReq](#InventDimPurchReq)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[InventDimReceiptsList](#InventDimReceiptsList)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[InventDimRFQ](#InventDimRFQ)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[ItemDimPlacement](#ItemDimPlacement)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[ItemDimSeparator](#ItemDimSeparator)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[itemNameAndTxt2Description](#itemNameAndTxt2Description)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[ItemNum](#ItemNum)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[Key](#Key)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrePrintLevelPurchAgreement](#PrePrintLevelPurchAgreement)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrePrintLevelPurchorder](#PrePrintLevelPurchorder)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrePrintLevelPurchOrderConfirmation](#PrePrintLevelPurchOrderConfirmation)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrePrintLevelPurchRFQ](#PrePrintLevelPurchRFQ)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrintAgreementClassification](#PrintAgreementClassification)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrintCashDiscount](#PrintCashDiscount)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrintContractReference](#PrintContractReference)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrintDeliveryTerm](#PrintDeliveryTerm)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrintEuroAmount](#PrintEuroAmount)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrintIntracomVAT](#PrintIntracomVAT)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrintInvoiceVATNum](#PrintInvoiceVATNum)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrintMaxIsEnforced](#PrintMaxIsEnforced)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrintModeOfDelivery](#PrintModeOfDelivery)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrintPayment](#PrintPayment)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[TaxPrintTaxFreeBalance](#TaxPrintTaxFreeBalance)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[TaxSpecPrintLevel](#TaxSpecPrintLevel)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[TotalsFirstLastPage](#TotalsFirstLastPage)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrintPurchAgreementVATNum](#PrintPurchAgreementVATNum)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrintPurchOrderVATNum](#PrintPurchOrderVATNum)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrintPurchPackingSlipVATNum](#PrintPurchPackingSlipVATNum)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrintPurchReceiptsListVATNum](#PrintPurchReceiptsListVATNum)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[PrintPurchRFQVATNum](#PrintPurchRFQVATNum)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[DataAreaId](#DataAreaId)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="VendFormletterParameters.md" target="_blank">Parameter/VendFormletterParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendFormletterParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CreditNotePrintType_RU name="CreditNotePrintType_RU">CreditNotePrintType_RU</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditNotePrintType_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExternalItemOverwriteAppend name="ExternalItemOverwriteAppend">ExternalItemOverwriteAppend</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalItemOverwriteAppend attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#HighlightUpdatedLines name="HighlightUpdatedLines">HighlightUpdatedLines</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HighlightUpdatedLines attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#HighlightUpdatedLinesConfirmationRequest name="HighlightUpdatedLinesConfirmationRequest">HighlightUpdatedLinesConfirmationRequest</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HighlightUpdatedLinesConfirmationRequest attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventDimInvoice name="InventDimInvoice">InventDimInvoice</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventDimPackingSlip name="InventDimPackingSlip">InventDimPackingSlip</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimPackingSlip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventDimPurchaseAgreement name="InventDimPurchaseAgreement">InventDimPurchaseAgreement</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimPurchaseAgreement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventDimPurchaseOrder name="InventDimPurchaseOrder">InventDimPurchaseOrder</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimPurchaseOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventDimPurchOrderConfirmationRequest name="InventDimPurchOrderConfirmationRequest">InventDimPurchOrderConfirmationRequest</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimPurchOrderConfirmationRequest attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventDimPurchReq name="InventDimPurchReq">InventDimPurchReq</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimPurchReq attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventDimReceiptsList name="InventDimReceiptsList">InventDimReceiptsList</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimReceiptsList attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventDimRFQ name="InventDimRFQ">InventDimRFQ</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimRFQ attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ItemDimPlacement name="ItemDimPlacement">ItemDimPlacement</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemDimPlacement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ItemDimSeparator name="ItemDimSeparator">ItemDimSeparator</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product dimension separator</td></tr><tr><td>dataFormat</td><td>char</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemDimSeparator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product dimension separator</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.big**  
</details>

### <a href=#itemNameAndTxt2Description name="itemNameAndTxt2Description">itemNameAndTxt2Description</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the itemNameAndTxt2Description attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ItemNum name="ItemNum">ItemNum</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#PrePrintLevelPurchAgreement name="PrePrintLevelPurchAgreement">PrePrintLevelPurchAgreement</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Paper format</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePrintLevelPurchAgreement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Paper format</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PrePrintLevelPurchorder name="PrePrintLevelPurchorder">PrePrintLevelPurchorder</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Paper format</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePrintLevelPurchorder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Paper format</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PrePrintLevelPurchOrderConfirmation name="PrePrintLevelPurchOrderConfirmation">PrePrintLevelPurchOrderConfirmation</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Paper format</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePrintLevelPurchOrderConfirmation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Paper format</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PrePrintLevelPurchRFQ name="PrePrintLevelPurchRFQ">PrePrintLevelPurchRFQ</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Paper format</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePrintLevelPurchRFQ attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Paper format</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PrintAgreementClassification name="PrintAgreementClassification">PrintAgreementClassification</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintAgreementClassification attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintCashDiscount name="PrintCashDiscount">PrintCashDiscount</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintCashDiscount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintContractReference name="PrintContractReference">PrintContractReference</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintContractReference attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintDeliveryTerm name="PrintDeliveryTerm">PrintDeliveryTerm</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintDeliveryTerm attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintEuroAmount name="PrintEuroAmount">PrintEuroAmount</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintEuroAmount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintIntracomVAT name="PrintIntracomVAT">PrintIntracomVAT</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Print EU sales tax on Spanish invoices</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintIntracomVAT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Print EU sales tax on Spanish invoices</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PrintInvoiceVATNum name="PrintInvoiceVATNum">PrintInvoiceVATNum</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintInvoiceVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintMaxIsEnforced name="PrintMaxIsEnforced">PrintMaxIsEnforced</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintMaxIsEnforced attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintModeOfDelivery name="PrintModeOfDelivery">PrintModeOfDelivery</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintModeOfDelivery attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintPayment name="PrintPayment">PrintPayment</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintPayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxPrintTaxFreeBalance name="TaxPrintTaxFreeBalance">TaxPrintTaxFreeBalance</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPrintTaxFreeBalance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxSpecPrintLevel name="TaxSpecPrintLevel">TaxSpecPrintLevel</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSpecPrintLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TotalsFirstLastPage name="TotalsFirstLastPage">TotalsFirstLastPage</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Totals</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalsFirstLastPage attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Totals</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PrintPurchAgreementVATNum name="PrintPurchAgreementVATNum">PrintPurchAgreementVATNum</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintPurchAgreementVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintPurchOrderVATNum name="PrintPurchOrderVATNum">PrintPurchOrderVATNum</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintPurchOrderVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintPurchPackingSlipVATNum name="PrintPurchPackingSlipVATNum">PrintPurchPackingSlipVATNum</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintPurchPackingSlipVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintPurchReceiptsListVATNum name="PrintPurchReceiptsListVATNum">PrintPurchReceiptsListVATNum</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintPurchReceiptsListVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintPurchRFQVATNum name="PrintPurchRFQVATNum">PrintPurchRFQVATNum</a>

First included in: Parameter/VendFormletterParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintPurchRFQVATNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/VendFormletterParameters (this entity)  

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/VendFormletterParameters (this entity)  

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
