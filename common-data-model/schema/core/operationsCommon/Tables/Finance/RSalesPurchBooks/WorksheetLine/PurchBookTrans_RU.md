---
title: PurchBookTrans_RU in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Purchase book lines in WorksheetLine(PurchBookTrans_RU)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/RSalesPurchBooks/WorksheetLine/PurchBookTrans_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchBookTrans_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase book lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[AccountName](#AccountName)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[AccountNum](#AccountNum)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[AmountInclVAT](#AmountInclVAT)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[AmountLiableToVAT0](#AmountLiableToVAT0)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[AmountLiableToVAT10](#AmountLiableToVAT10)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[AmountLiableToVAT20](#AmountLiableToVAT20)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[AmountNotLiableToVAT](#AmountNotLiableToVAT)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[Annulment](#Annulment)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[CorrectedFactureDate](#CorrectedFactureDate)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[CorrectedFactureExternalId](#CorrectedFactureExternalId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[CorrectedPurchBookTable_RU](#CorrectedPurchBookTable_RU)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[CorrectionType](#CorrectionType)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[CountryGTD](#CountryGTD)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[DeliveryDate](#DeliveryDate)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[FactureDate](#FactureDate)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[FactureDate_External](#FactureDate_External)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[FactureExternalId](#FactureExternalId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[FactureId](#FactureId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[FactureJour_RU](#FactureJour_RU)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[InvoiceCompany](#InvoiceCompany)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[InvoiceRecIdRef](#InvoiceRecIdRef)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[JointCorrection](#JointCorrection)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[LineNum](#LineNum)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[PaymentCompany](#PaymentCompany)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[PaymentDate](#PaymentDate)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[PaymentRecIdRef](#PaymentRecIdRef)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[PurchBookTable_RU](#PurchBookTable_RU)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[PurchBookTransDate](#PurchBookTransDate)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[RefOriginalFacture](#RefOriginalFacture)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[RefRevisedFacture](#RefRevisedFacture)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[RefTableId](#RefTableId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[ReverseDate](#ReverseDate)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[ReverseTrans](#ReverseTrans)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[RevisionSeqNumber](#RevisionSeqNumber)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[RevisionType](#RevisionType)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[SettlementDate](#SettlementDate)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[TaxAmountVAT10](#TaxAmountVAT10)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[TaxAmountVAT20](#TaxAmountVAT20)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[TransType](#TransType)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[AmountCurInclVAT](#AmountCurInclVAT)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[CommissionAgent](#CommissionAgent)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[CurrencyCode](#CurrencyCode)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[OperationTypeCodes](#OperationTypeCodes)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[PaymDocumentNum](#PaymDocumentNum)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[DataAreaId](#DataAreaId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[Relationship_CorrectedPurchBookTable_RURelationshipId](#Relationship_CorrectedPurchBookTable_RURelationshipId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[Relationship_CustTransInvoiceRelationshipId](#Relationship_CustTransInvoiceRelationshipId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[Relationship_CustTransPaymentRelationshipId](#Relationship_CustTransPaymentRelationshipId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[Relationship_EmplTransRelationshipId](#Relationship_EmplTransRelationshipId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[Relationship_FactureJourRelationshipId](#Relationship_FactureJourRelationshipId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[Relationship_FactureJour_RURelationshipId](#Relationship_FactureJour_RURelationshipId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[Relationship_FactureJourOriginalRelationshipId](#Relationship_FactureJourOriginalRelationshipId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[Relationship_FactureJourRevisedRelationshipId](#Relationship_FactureJourRevisedRelationshipId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[Relationship_PurchBookTable_RURelationshipId](#Relationship_PurchBookTable_RURelationshipId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[Relationship_VendTransInvoiceRelationshipId](#Relationship_VendTransInvoiceRelationshipId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[Relationship_VendTransPaymentRelationshipId](#Relationship_VendTransPaymentRelationshipId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[Relationship_VendTable_ComissionAgentRelationshipId](#Relationship_VendTable_ComissionAgentRelationshipId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PurchBookTrans_RU.md" target="_blank">WorksheetLine/PurchBookTrans_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchBookTrans_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountName name="AccountName">AccountName</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum name="AccountNum">AccountNum</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountInclVAT name="AmountInclVAT">AmountInclVAT</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInclVAT attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountLiableToVAT0 name="AmountLiableToVAT0">AmountLiableToVAT0</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount w\o VAT</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountLiableToVAT0 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount w\o VAT</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountLiableToVAT10 name="AmountLiableToVAT10">AmountLiableToVAT10</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount w\o VAT</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountLiableToVAT10 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount w\o VAT</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountLiableToVAT20 name="AmountLiableToVAT20">AmountLiableToVAT20</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount w\o VAT</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountLiableToVAT20 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount w\o VAT</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountNotLiableToVAT name="AmountNotLiableToVAT">AmountNotLiableToVAT</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Base amount (not liable to VAT)</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountNotLiableToVAT attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Base amount (not liable to VAT)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Annulment name="Annulment">Annulment</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Annulment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CorrectedFactureDate name="CorrectedFactureDate">CorrectedFactureDate</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Facture date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedFactureDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Facture date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#CorrectedFactureExternalId name="CorrectedFactureExternalId">CorrectedFactureExternalId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedFactureExternalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedPurchBookTable_RU name="CorrectedPurchBookTable_RU">CorrectedPurchBookTable_RU</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedPurchBookTable_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CorrectionType name="CorrectionType">CorrectionType</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CountryGTD name="CountryGTD">CountryGTD</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom decl. numbers</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryGTD attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Custom decl. numbers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryDate name="DeliveryDate">DeliveryDate</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delivery date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delivery date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#FactureDate name="FactureDate">FactureDate</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactureDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#FactureDate_External name="FactureDate_External">FactureDate_External</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactureDate_External attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#FactureExternalId name="FactureExternalId">FactureExternalId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactureExternalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FactureId name="FactureId">FactureId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactureId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FactureJour_RU name="FactureJour_RU">FactureJour_RU</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactureJour_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InvoiceCompany name="InvoiceCompany">InvoiceCompany</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Legal entity of the invoice</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Legal entity of the invoice</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceRecIdRef name="InvoiceRecIdRef">InvoiceRecIdRef</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice reference</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceRecIdRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice reference</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#JointCorrection name="JointCorrection">JointCorrection</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JointCorrection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PaymentCompany name="PaymentCompany">PaymentCompany</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Legal entity of the payment</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Legal entity of the payment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentDate name="PaymentDate">PaymentDate</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#PaymentRecIdRef name="PaymentRecIdRef">PaymentRecIdRef</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment reference</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentRecIdRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment reference</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchBookTable_RU name="PurchBookTable_RU">PurchBookTable_RU</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchBookTable_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchBookTransDate name="PurchBookTransDate">PurchBookTransDate</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchBookTransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#RefOriginalFacture name="RefOriginalFacture">RefOriginalFacture</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefOriginalFacture attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefRevisedFacture name="RefRevisedFacture">RefRevisedFacture</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRevisedFacture attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefTableId name="RefTableId">RefTableId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReverseDate name="ReverseDate">ReverseDate</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ReverseTrans name="ReverseTrans">ReverseTrans</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RevisionSeqNumber name="RevisionSeqNumber">RevisionSeqNumber</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevisionSeqNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RevisionType name="RevisionType">RevisionType</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevisionType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SettlementDate name="SettlementDate">SettlementDate</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date of settlement</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date of settlement</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#TaxAmountVAT10 name="TaxAmountVAT10">TaxAmountVAT10</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountVAT10 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmountVAT20 name="TaxAmountVAT20">TaxAmountVAT20</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountVAT20 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransType name="TransType">TransType</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AmountCurInclVAT name="AmountCurInclVAT">AmountCurInclVAT</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCurInclVAT attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CommissionAgent name="CommissionAgent">CommissionAgent</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommissionAgent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

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

### <a href=#OperationTypeCodes name="OperationTypeCodes">OperationTypeCodes</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationTypeCodes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymDocumentNum name="PaymDocumentNum">PaymDocumentNum</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment document number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymDocumentNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment document number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

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

### <a href=#Relationship_CorrectedPurchBookTable_RURelationshipId name="Relationship_CorrectedPurchBookTable_RURelationshipId">Relationship_CorrectedPurchBookTable_RURelationshipId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CorrectedPurchBookTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/PurchBookTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/RSalesPurchBooks/WorksheetHeader/PurchBookTable_RU.cdm.json/PurchBookTable_RU</a></td><td><a href="../WorksheetHeader/PurchBookTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTransInvoiceRelationshipId name="Relationship_CustTransInvoiceRelationshipId">Relationship_CustTransInvoiceRelationshipId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTransInvoiceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Transaction/CustTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustTrans.cdm.json/CustTrans</a></td><td><a href="../../AccountsReceivable/Transaction/CustTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTransPaymentRelationshipId name="Relationship_CustTransPaymentRelationshipId">Relationship_CustTransPaymentRelationshipId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTransPaymentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Transaction/CustTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustTrans.cdm.json/CustTrans</a></td><td><a href="../../AccountsReceivable/Transaction/CustTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EmplTransRelationshipId name="Relationship_EmplTransRelationshipId">Relationship_EmplTransRelationshipId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EmplTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Expense/Transaction/EmplTrans_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Expense/Transaction/EmplTrans_RU.cdm.json/EmplTrans_RU</a></td><td><a href="../../Expense/Transaction/EmplTrans_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FactureJourRelationshipId name="Relationship_FactureJourRelationshipId">Relationship_FactureJourRelationshipId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FactureJourRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/FactureJour_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/RSalesPurchBooks/WorksheetHeader/FactureJour_RU.cdm.json/FactureJour_RU</a></td><td><a href="../WorksheetHeader/FactureJour_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FactureJour_RURelationshipId name="Relationship_FactureJour_RURelationshipId">Relationship_FactureJour_RURelationshipId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FactureJour_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/FactureJour_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/RSalesPurchBooks/WorksheetHeader/FactureJour_RU.cdm.json/FactureJour_RU</a></td><td><a href="../WorksheetHeader/FactureJour_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FactureJourOriginalRelationshipId name="Relationship_FactureJourOriginalRelationshipId">Relationship_FactureJourOriginalRelationshipId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FactureJourOriginalRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/FactureJour_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/RSalesPurchBooks/WorksheetHeader/FactureJour_RU.cdm.json/FactureJour_RU</a></td><td><a href="../WorksheetHeader/FactureJour_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FactureJourRevisedRelationshipId name="Relationship_FactureJourRevisedRelationshipId">Relationship_FactureJourRevisedRelationshipId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FactureJourRevisedRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/FactureJour_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/RSalesPurchBooks/WorksheetHeader/FactureJour_RU.cdm.json/FactureJour_RU</a></td><td><a href="../WorksheetHeader/FactureJour_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchBookTable_RURelationshipId name="Relationship_PurchBookTable_RURelationshipId">Relationship_PurchBookTable_RURelationshipId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchBookTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/PurchBookTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/RSalesPurchBooks/WorksheetHeader/PurchBookTable_RU.cdm.json/PurchBookTable_RU</a></td><td><a href="../WorksheetHeader/PurchBookTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

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

### <a href=#Relationship_VendTransInvoiceRelationshipId name="Relationship_VendTransInvoiceRelationshipId">Relationship_VendTransInvoiceRelationshipId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTransInvoiceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsPayable/Transaction/VendTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Transaction/VendTrans.cdm.json/VendTrans</a></td><td><a href="../../AccountsPayable/Transaction/VendTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTransPaymentRelationshipId name="Relationship_VendTransPaymentRelationshipId">Relationship_VendTransPaymentRelationshipId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTransPaymentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsPayable/Transaction/VendTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Transaction/VendTrans.cdm.json/VendTrans</a></td><td><a href="../../AccountsPayable/Transaction/VendTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTable_ComissionAgentRelationshipId name="Relationship_VendTable_ComissionAgentRelationshipId">Relationship_VendTable_ComissionAgentRelationshipId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTable_ComissionAgentRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/PurchBookTrans_RU (this entity)  

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
