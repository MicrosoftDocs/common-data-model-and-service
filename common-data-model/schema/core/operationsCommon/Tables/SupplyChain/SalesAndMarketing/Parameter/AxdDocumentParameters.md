---
title: AxdDocumentParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# AxdDocumentParameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Parameter/AxdDocumentParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AxdDocumentParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[ProfitLossJournalNameId](#ProfitLossJournalNameId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[InvoiceRegisterJournalName](#InvoiceRegisterJournalName)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[RouteCardJournalNameId](#RouteCardJournalNameId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[CalculateMultilineDiscount](#CalculateMultilineDiscount)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[CalculateTotalDiscount](#CalculateTotalDiscount)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[CheckCreditLimit](#CheckCreditLimit)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[CheckCreditMax](#CheckCreditMax)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[CheckMultipleWareHouses](#CheckMultipleWareHouses)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[CountJournalNameId](#CountJournalNameId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[CreditLineError](#CreditLineError)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[CreditRemaining](#CreditRemaining)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[CustTableUpdateCurrency](#CustTableUpdateCurrency)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[DocuTypeId](#DocuTypeId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[FreeTextInvoiceLedgerDimension](#FreeTextInvoiceLedgerDimension)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[Key](#Key)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[PriceDiscJournalName](#PriceDiscJournalName)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[PrintCallTag](#PrintCallTag)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[PrintCODLabel](#PrintCODLabel)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[Printout](#Printout)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[PrintPackingSlip](#PrintPackingSlip)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[PrintShippingLabel](#PrintShippingLabel)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[ProdPickingListAutoPosting](#ProdPickingListAutoPosting)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[ProdPickingListJournalNameId](#ProdPickingListJournalNameId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[ProjJournalNameId](#ProjJournalNameId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[ReduceOnHand](#ReduceOnHand)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[RouteCardAutoPosting](#RouteCardAutoPosting)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[SalesType](#SalesType)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[SpecQty](#SpecQty)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[Storno](#Storno)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[StornoPhysical_RU](#StornoPhysical_RU)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[TransferJournalNameId](#TransferJournalNameId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[UpdateNow](#UpdateNow)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[DataAreaId](#DataAreaId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[Relationship_CountJournalNameRelationshipId](#Relationship_CountJournalNameRelationshipId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[Relationship_DocuTypeRelationshipId](#Relationship_DocuTypeRelationshipId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[Relationship_FreeTextInvoiceLedgerDimensionRelationshipId](#Relationship_FreeTextInvoiceLedgerDimensionRelationshipId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[Relationship_InvoiceRegisterJournalNameRelationshipId](#Relationship_InvoiceRegisterJournalNameRelationshipId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[Relationship_PriceDiscAdmNameRelationshipId](#Relationship_PriceDiscAdmNameRelationshipId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[Relationship_ProdPickingListJournalNameRelationshipId](#Relationship_ProdPickingListJournalNameRelationshipId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[Relationship_ProfitLossJournalNameRelationshipId](#Relationship_ProfitLossJournalNameRelationshipId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[Relationship_ProjJournalNameRelationshipId](#Relationship_ProjJournalNameRelationshipId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[Relationship_RouteCardJournalNameRelationshipId](#Relationship_RouteCardJournalNameRelationshipId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[Relationship_TransferJournalNameRelationshipId](#Relationship_TransferJournalNameRelationshipId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AxdDocumentParameters.md" target="_blank">Parameter/AxdDocumentParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AxdDocumentParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProfitLossJournalNameId name="ProfitLossJournalNameId">ProfitLossJournalNameId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitLossJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceRegisterJournalName name="InvoiceRegisterJournalName">InvoiceRegisterJournalName</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceRegisterJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteCardJournalNameId name="RouteCardJournalNameId">RouteCardJournalNameId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteCardJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CalculateMultilineDiscount name="CalculateMultilineDiscount">CalculateMultilineDiscount</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculateMultilineDiscount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CalculateTotalDiscount name="CalculateTotalDiscount">CalculateTotalDiscount</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalculateTotalDiscount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CheckCreditLimit name="CheckCreditLimit">CheckCreditLimit</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckCreditLimit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CheckCreditMax name="CheckCreditMax">CheckCreditMax</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckCreditMax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CheckMultipleWareHouses name="CheckMultipleWareHouses">CheckMultipleWareHouses</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckMultipleWareHouses attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CountJournalNameId name="CountJournalNameId">CountJournalNameId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditLineError name="CreditLineError">CreditLineError</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLineError attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CreditRemaining name="CreditRemaining">CreditRemaining</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditRemaining attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustTableUpdateCurrency name="CustTableUpdateCurrency">CustTableUpdateCurrency</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustTableUpdateCurrency attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocuTypeId name="DocuTypeId">DocuTypeId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreeTextInvoiceLedgerDimension name="FreeTextInvoiceLedgerDimension">FreeTextInvoiceLedgerDimension</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreeTextInvoiceLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#PriceDiscJournalName name="PriceDiscJournalName">PriceDiscJournalName</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceDiscJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintCallTag name="PrintCallTag">PrintCallTag</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintCallTag attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintCODLabel name="PrintCODLabel">PrintCODLabel</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintCODLabel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Printout name="Printout">Printout</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Printout attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintPackingSlip name="PrintPackingSlip">PrintPackingSlip</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintPackingSlip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintShippingLabel name="PrintShippingLabel">PrintShippingLabel</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintShippingLabel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProdPickingListAutoPosting name="ProdPickingListAutoPosting">ProdPickingListAutoPosting</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProdPickingListAutoPosting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProdPickingListJournalNameId name="ProdPickingListJournalNameId">ProdPickingListJournalNameId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProdPickingListJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjJournalNameId name="ProjJournalNameId">ProjJournalNameId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReduceOnHand name="ReduceOnHand">ReduceOnHand</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReduceOnHand attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RouteCardAutoPosting name="RouteCardAutoPosting">RouteCardAutoPosting</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteCardAutoPosting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SalesType name="SalesType">SalesType</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SpecQty name="SpecQty">SpecQty</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecQty attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Storno name="Storno">Storno</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Storno attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StornoPhysical_RU name="StornoPhysical_RU">StornoPhysical_RU</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StornoPhysical_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransferJournalNameId name="TransferJournalNameId">TransferJournalNameId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UpdateNow name="UpdateNow">UpdateNow</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateNow attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

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

### <a href=#Relationship_CountJournalNameRelationshipId name="Relationship_CountJournalNameRelationshipId">Relationship_CountJournalNameRelationshipId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CountJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Group/InventJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventJournalName.cdm.json/InventJournalName</a></td><td><a href="../../Inventory/Group/InventJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DocuTypeRelationshipId name="Relationship_DocuTypeRelationshipId">Relationship_DocuTypeRelationshipId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DocuTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/DocuType.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/DocuType.cdm.json/DocuType</a></td><td><a href="../../../System/SystemAdministration/Group/DocuType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FreeTextInvoiceLedgerDimensionRelationshipId name="Relationship_FreeTextInvoiceLedgerDimensionRelationshipId">Relationship_FreeTextInvoiceLedgerDimensionRelationshipId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FreeTextInvoiceLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InvoiceRegisterJournalNameRelationshipId name="Relationship_InvoiceRegisterJournalNameRelationshipId">Relationship_InvoiceRegisterJournalNameRelationshipId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InvoiceRegisterJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountingFoundation/Group/LedgerJournalName.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Group/LedgerJournalName.cdm.json/LedgerJournalName</a></td><td><a href="../../../Finance/AccountingFoundation/Group/LedgerJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PriceDiscAdmNameRelationshipId name="Relationship_PriceDiscAdmNameRelationshipId">Relationship_PriceDiscAdmNameRelationshipId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PriceDiscAdmNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/PriceDiscAdmName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/PriceDiscAdmName.cdm.json/PriceDiscAdmName</a></td><td><a href="../Group/PriceDiscAdmName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProdPickingListJournalNameRelationshipId name="Relationship_ProdPickingListJournalNameRelationshipId">Relationship_ProdPickingListJournalNameRelationshipId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProdPickingListJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/Group/ProdJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/ProdJournalName.cdm.json/ProdJournalName</a></td><td><a href="../../ProductionControl/Group/ProdJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProfitLossJournalNameRelationshipId name="Relationship_ProfitLossJournalNameRelationshipId">Relationship_ProfitLossJournalNameRelationshipId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProfitLossJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Group/InventJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventJournalName.cdm.json/InventJournalName</a></td><td><a href="../../Inventory/Group/InventJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjJournalNameRelationshipId name="Relationship_ProjJournalNameRelationshipId">Relationship_ProjJournalNameRelationshipId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjJournalName.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjJournalName.cdm.json/ProjJournalName</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RouteCardJournalNameRelationshipId name="Relationship_RouteCardJournalNameRelationshipId">Relationship_RouteCardJournalNameRelationshipId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RouteCardJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/Group/ProdJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/ProdJournalName.cdm.json/ProdJournalName</a></td><td><a href="../../ProductionControl/Group/ProdJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransferJournalNameRelationshipId name="Relationship_TransferJournalNameRelationshipId">Relationship_TransferJournalNameRelationshipId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransferJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Group/InventJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventJournalName.cdm.json/InventJournalName</a></td><td><a href="../../Inventory/Group/InventJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/AxdDocumentParameters (this entity)  

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
