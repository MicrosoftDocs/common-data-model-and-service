---
title: SalesBookTrans_RU - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# SalesBookTrans_RU

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/RSalesPurchBooks/WorksheetLine/SalesBookTrans_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SalesBookTrans_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[FactureId](#FactureId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[AccountName](#AccountName)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[AccountNum](#AccountNum)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[AmountInclVAT](#AmountInclVAT)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[AmountLiableToVAT0](#AmountLiableToVAT0)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[AmountLiableToVAT10](#AmountLiableToVAT10)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[AmountLiableToVAT20](#AmountLiableToVAT20)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[AmountNotLiableToVAT](#AmountNotLiableToVAT)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Annulment](#Annulment)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[CorrectedFactureDate](#CorrectedFactureDate)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[CorrectedFactureExternalId](#CorrectedFactureExternalId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[CorrectedSalesBookTable_RU](#CorrectedSalesBookTable_RU)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[CorrectingFactureId](#CorrectingFactureId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[CorrectionType](#CorrectionType)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[FactureDate](#FactureDate)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[FactureDate_External](#FactureDate_External)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[FactureExternalId](#FactureExternalId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[FactureJour_RU](#FactureJour_RU)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[JointCorrection](#JointCorrection)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[LineNum](#LineNum)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[PaymentCompany](#PaymentCompany)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[PaymentDate](#PaymentDate)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[PaymentRecIdRef](#PaymentRecIdRef)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[RefOriginalFacture](#RefOriginalFacture)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[RefRevisedFacture](#RefRevisedFacture)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[RefTableId](#RefTableId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[ReverseDate](#ReverseDate)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[ReverseTrans](#ReverseTrans)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[RevisionSeqNumber](#RevisionSeqNumber)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[RevisionType](#RevisionType)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[SalesBookTable_RU](#SalesBookTable_RU)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[SettlementDate](#SettlementDate)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[TaxAmountVAT10](#TaxAmountVAT10)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[TaxAmountVAT20](#TaxAmountVAT20)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[TransType](#TransType)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[AmountCurInclVAT](#AmountCurInclVAT)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[CommissionAgent](#CommissionAgent)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[CurrencyCode](#CurrencyCode)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[OperationTypeCodes](#OperationTypeCodes)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[PaymDocumentNum](#PaymDocumentNum)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[DataAreaId](#DataAreaId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_CustTransPaymentRelationshipId](#Relationship_CustTransPaymentRelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_FactureJourRelationshipId](#Relationship_FactureJourRelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_FactureJour_AmountDiffRelationshipId](#Relationship_FactureJour_AmountDiffRelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_FactureJour_CreditNoteRelationshipId](#Relationship_FactureJour_CreditNoteRelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_FactureJour_InvoiceRelationshipId](#Relationship_FactureJour_InvoiceRelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_FactureJour_PrepaymentRelationshipId](#Relationship_FactureJour_PrepaymentRelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_FactureJour_RURelationshipId](#Relationship_FactureJour_RURelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_FactureJour_TaxCorrection_CustRelationshipId](#Relationship_FactureJour_TaxCorrection_CustRelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_FactureJour_TaxCorrection_CustPurchRelationshipId](#Relationship_FactureJour_TaxCorrection_CustPurchRelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_FactureJour_TaxCorrection_VendRelationshipId](#Relationship_FactureJour_TaxCorrection_VendRelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_FactureJourOriginalRelationshipId](#Relationship_FactureJourOriginalRelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_FactureJourRevisedRelationshipId](#Relationship_FactureJourRevisedRelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_RefCorrectingFactureJour_RURelationshipId](#Relationship_RefCorrectingFactureJour_RURelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_SalesBookTable_RURelationshipId](#Relationship_SalesBookTable_RURelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_SalesBookTableCorrected_RURelationshipId](#Relationship_SalesBookTableCorrected_RURelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_CustTable_CommissionAgentRelationshipId](#Relationship_CustTable_CommissionAgentRelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="SalesBookTrans_RU.md" target="_blank">WorksheetLine/SalesBookTrans_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SalesBookTrans_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FactureId name="FactureId">FactureId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

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

### <a href=#AccountName name="AccountName">AccountName</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum name="AccountNum">AccountNum</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

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

### <a href=#AmountInclVAT name="AmountInclVAT">AmountInclVAT</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountInclVAT attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountLiableToVAT0 name="AmountLiableToVAT0">AmountLiableToVAT0</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountLiableToVAT0 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountLiableToVAT10 name="AmountLiableToVAT10">AmountLiableToVAT10</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountLiableToVAT10 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountLiableToVAT20 name="AmountLiableToVAT20">AmountLiableToVAT20</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountLiableToVAT20 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountNotLiableToVAT name="AmountNotLiableToVAT">AmountNotLiableToVAT</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountNotLiableToVAT attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Annulment name="Annulment">Annulment</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Annulment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CorrectedFactureDate name="CorrectedFactureDate">CorrectedFactureDate</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedFactureDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#CorrectedFactureExternalId name="CorrectedFactureExternalId">CorrectedFactureExternalId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedFactureExternalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectedSalesBookTable_RU name="CorrectedSalesBookTable_RU">CorrectedSalesBookTable_RU</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectedSalesBookTable_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CorrectingFactureId name="CorrectingFactureId">CorrectingFactureId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectingFactureId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionType name="CorrectionType">CorrectionType</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FactureDate name="FactureDate">FactureDate</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactureDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#FactureDate_External name="FactureDate_External">FactureDate_External</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactureDate_External attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#FactureExternalId name="FactureExternalId">FactureExternalId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactureExternalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FactureJour_RU name="FactureJour_RU">FactureJour_RU</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

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

### <a href=#JointCorrection name="JointCorrection">JointCorrection</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JointCorrection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PaymentCompany name="PaymentCompany">PaymentCompany</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentDate name="PaymentDate">PaymentDate</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PaymentRecIdRef name="PaymentRecIdRef">PaymentRecIdRef</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentRecIdRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefOriginalFacture name="RefOriginalFacture">RefOriginalFacture</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefOriginalFacture attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefRevisedFacture name="RefRevisedFacture">RefRevisedFacture</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRevisedFacture attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefTableId name="RefTableId">RefTableId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReverseDate name="ReverseDate">ReverseDate</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ReverseTrans name="ReverseTrans">ReverseTrans</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReverseTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RevisionSeqNumber name="RevisionSeqNumber">RevisionSeqNumber</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevisionSeqNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RevisionType name="RevisionType">RevisionType</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RevisionType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SalesBookTable_RU name="SalesBookTable_RU">SalesBookTable_RU</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesBookTable_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SettlementDate name="SettlementDate">SettlementDate</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#TaxAmountVAT10 name="TaxAmountVAT10">TaxAmountVAT10</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountVAT10 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAmountVAT20 name="TaxAmountVAT20">TaxAmountVAT20</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountVAT20 attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransType name="TransType">TransType</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AmountCurInclVAT name="AmountCurInclVAT">AmountCurInclVAT</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCurInclVAT attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CommissionAgent name="CommissionAgent">CommissionAgent</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommissionAgent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

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

### <a href=#OperationTypeCodes name="OperationTypeCodes">OperationTypeCodes</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationTypeCodes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymDocumentNum name="PaymDocumentNum">PaymDocumentNum</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymDocumentNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

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

### <a href=#Relationship_CustTableRelationshipId name="Relationship_CustTableRelationshipId">Relationship_CustTableRelationshipId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTableRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CustTransPaymentRelationshipId name="Relationship_CustTransPaymentRelationshipId">Relationship_CustTransPaymentRelationshipId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

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

### <a href=#Relationship_FactureJourRelationshipId name="Relationship_FactureJourRelationshipId">Relationship_FactureJourRelationshipId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

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

### <a href=#Relationship_FactureJour_AmountDiffRelationshipId name="Relationship_FactureJour_AmountDiffRelationshipId">Relationship_FactureJour_AmountDiffRelationshipId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FactureJour_AmountDiffRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_FactureJour_CreditNoteRelationshipId name="Relationship_FactureJour_CreditNoteRelationshipId">Relationship_FactureJour_CreditNoteRelationshipId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FactureJour_CreditNoteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_FactureJour_InvoiceRelationshipId name="Relationship_FactureJour_InvoiceRelationshipId">Relationship_FactureJour_InvoiceRelationshipId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FactureJour_InvoiceRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_FactureJour_PrepaymentRelationshipId name="Relationship_FactureJour_PrepaymentRelationshipId">Relationship_FactureJour_PrepaymentRelationshipId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FactureJour_PrepaymentRelationshipId attribute are listed below.</summary>

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

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

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

### <a href=#Relationship_FactureJour_TaxCorrection_CustRelationshipId name="Relationship_FactureJour_TaxCorrection_CustRelationshipId">Relationship_FactureJour_TaxCorrection_CustRelationshipId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FactureJour_TaxCorrection_CustRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_FactureJour_TaxCorrection_CustPurchRelationshipId name="Relationship_FactureJour_TaxCorrection_CustPurchRelationshipId">Relationship_FactureJour_TaxCorrection_CustPurchRelationshipId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FactureJour_TaxCorrection_CustPurchRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_FactureJour_TaxCorrection_VendRelationshipId name="Relationship_FactureJour_TaxCorrection_VendRelationshipId">Relationship_FactureJour_TaxCorrection_VendRelationshipId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FactureJour_TaxCorrection_VendRelationshipId attribute are listed below.</summary>

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

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

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

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

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

### <a href=#Relationship_RefCorrectingFactureJour_RURelationshipId name="Relationship_RefCorrectingFactureJour_RURelationshipId">Relationship_RefCorrectingFactureJour_RURelationshipId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RefCorrectingFactureJour_RURelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SalesBookTable_RURelationshipId name="Relationship_SalesBookTable_RURelationshipId">Relationship_SalesBookTable_RURelationshipId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesBookTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/SalesBookTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/RSalesPurchBooks/WorksheetHeader/SalesBookTable_RU.cdm.json/SalesBookTable_RU</a></td><td><a href="../WorksheetHeader/SalesBookTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesBookTableCorrected_RURelationshipId name="Relationship_SalesBookTableCorrected_RURelationshipId">Relationship_SalesBookTableCorrected_RURelationshipId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesBookTableCorrected_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/SalesBookTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/RSalesPurchBooks/WorksheetHeader/SalesBookTable_RU.cdm.json/SalesBookTable_RU</a></td><td><a href="../WorksheetHeader/SalesBookTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

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

### <a href=#Relationship_CustTable_CommissionAgentRelationshipId name="Relationship_CustTable_CommissionAgentRelationshipId">Relationship_CustTable_CommissionAgentRelationshipId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTable_CommissionAgentRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/SalesBookTrans_RU (this entity)  

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
