---
title: LedgerJournalTrans_W in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Order line information for other country contexts in WorksheetLine(LedgerJournalTrans_W)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/WorksheetLine/LedgerJournalTrans_W.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerJournalTrans_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Order line information for other country contexts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[CashRegisterTerminal](#CashRegisterTerminal)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[CategoryPurpose](#CategoryPurpose)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[ChargeBearer](#ChargeBearer)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[LocalInstrument](#LocalInstrument)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[ServiceLevel](#ServiceLevel)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[LedgerJournalTrans](#LedgerJournalTrans)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[EPaymCFDIConfirmNumber_MX](#EPaymCFDIConfirmNumber_MX)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[CFDIBeneficiaryRetains_MX](#CFDIBeneficiaryRetains_MX)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[CFDIFinancialSystem_MX](#CFDIFinancialSystem_MX)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[CFDIInterestBelongsDerivedFinOp_MX](#CFDIInterestBelongsDerivedFinOp_MX)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[CFDIInterestCashedInTheCurrentPeriod_MX](#CFDIInterestCashedInTheCurrentPeriod_MX)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[CFDIInterestLossAmount_MX](#CFDIInterestLossAmount_MX)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[CFDIInterestNominalAmount_MX](#CFDIInterestNominalAmount_MX)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[CFDIInterestRealAmount_MX](#CFDIInterestRealAmount_MX)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[WithholdingTypeCode_MX](#WithholdingTypeCode_MX)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[RefPurchInvoiceDate_IN](#RefPurchInvoiceDate_IN)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[RefPurchInvoiceId_IN](#RefPurchInvoiceId_IN)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[RefSalesInvoiceDate_IN](#RefSalesInvoiceDate_IN)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[RefSalesInvoiceId_IN](#RefSalesInvoiceId_IN)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[OrigPaymRefRecId_RU](#OrigPaymRefRecId_RU)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[OrigPaymRefTableId_RU](#OrigPaymRefTableId_RU)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[Relationship_LedgerJournalTransRelationshipId](#Relationship_LedgerJournalTransRelationshipId)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[Relationship_PaymentFormatCodeSets_CategoryPurposeRelationshipId](#Relationship_PaymentFormatCodeSets_CategoryPurposeRelationshipId)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[Relationship_PaymentFormatCodeSets_ChargeBearerRelationshipId](#Relationship_PaymentFormatCodeSets_ChargeBearerRelationshipId)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[Relationship_PaymentFormatCodeSets_LocalInstrumentRelationshipId](#Relationship_PaymentFormatCodeSets_LocalInstrumentRelationshipId)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[Relationship_PaymentFormatCodeSets_ServiceLevelRelationshipId](#Relationship_PaymentFormatCodeSets_ServiceLevelRelationshipId)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[Relationship_CashRegisterTerminal_WRelationshipId](#Relationship_CashRegisterTerminal_WRelationshipId)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[Relationship_CFDIWithholdingType_MXRelationshipId](#Relationship_CFDIWithholdingType_MXRelationshipId)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[Relationship_CustTransRelationshipId](#Relationship_CustTransRelationshipId)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[Relationship_VendTransRelationshipId](#Relationship_VendTransRelationshipId)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerJournalTrans_W.md" target="_blank">WorksheetLine/LedgerJournalTrans_W</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerJournalTrans_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CashRegisterTerminal name="CashRegisterTerminal">CashRegisterTerminal</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashRegisterTerminal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CategoryPurpose name="CategoryPurpose">CategoryPurpose</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryPurpose attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ChargeBearer name="ChargeBearer">ChargeBearer</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeBearer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LocalInstrument name="LocalInstrument">LocalInstrument</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocalInstrument attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceLevel name="ServiceLevel">ServiceLevel</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerJournalTrans name="LedgerJournalTrans">LedgerJournalTrans</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerJournalTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EPaymCFDIConfirmNumber_MX name="EPaymCFDIConfirmNumber_MX">EPaymCFDIConfirmNumber_MX</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPaymCFDIConfirmNumber_MX attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFDIBeneficiaryRetains_MX name="CFDIBeneficiaryRetains_MX">CFDIBeneficiaryRetains_MX</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIBeneficiaryRetains_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CFDIFinancialSystem_MX name="CFDIFinancialSystem_MX">CFDIFinancialSystem_MX</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIFinancialSystem_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CFDIInterestBelongsDerivedFinOp_MX name="CFDIInterestBelongsDerivedFinOp_MX">CFDIInterestBelongsDerivedFinOp_MX</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIInterestBelongsDerivedFinOp_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CFDIInterestCashedInTheCurrentPeriod_MX name="CFDIInterestCashedInTheCurrentPeriod_MX">CFDIInterestCashedInTheCurrentPeriod_MX</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIInterestCashedInTheCurrentPeriod_MX attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CFDIInterestLossAmount_MX name="CFDIInterestLossAmount_MX">CFDIInterestLossAmount_MX</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIInterestLossAmount_MX attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CFDIInterestNominalAmount_MX name="CFDIInterestNominalAmount_MX">CFDIInterestNominalAmount_MX</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIInterestNominalAmount_MX attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CFDIInterestRealAmount_MX name="CFDIInterestRealAmount_MX">CFDIInterestRealAmount_MX</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFDIInterestRealAmount_MX attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WithholdingTypeCode_MX name="WithholdingTypeCode_MX">WithholdingTypeCode_MX</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTypeCode_MX attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefPurchInvoiceDate_IN name="RefPurchInvoiceDate_IN">RefPurchInvoiceDate_IN</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefPurchInvoiceDate_IN attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#RefPurchInvoiceId_IN name="RefPurchInvoiceId_IN">RefPurchInvoiceId_IN</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefPurchInvoiceId_IN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefSalesInvoiceDate_IN name="RefSalesInvoiceDate_IN">RefSalesInvoiceDate_IN</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefSalesInvoiceDate_IN attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#RefSalesInvoiceId_IN name="RefSalesInvoiceId_IN">RefSalesInvoiceId_IN</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefSalesInvoiceId_IN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrigPaymRefRecId_RU name="OrigPaymRefRecId_RU">OrigPaymRefRecId_RU</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Original prepayment</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrigPaymRefRecId_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Original prepayment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OrigPaymRefTableId_RU name="OrigPaymRefTableId_RU">OrigPaymRefTableId_RU</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrigPaymRefTableId_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

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

### <a href=#Relationship_LedgerJournalTransRelationshipId name="Relationship_LedgerJournalTransRelationshipId">Relationship_LedgerJournalTransRelationshipId</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/WorksheetLine/LedgerJournalTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/WorksheetLine/LedgerJournalTrans.cdm.json/LedgerJournalTrans</a></td><td><a href="../../AccountingFoundation/WorksheetLine/LedgerJournalTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentFormatCodeSets_CategoryPurposeRelationshipId name="Relationship_PaymentFormatCodeSets_CategoryPurposeRelationshipId">Relationship_PaymentFormatCodeSets_CategoryPurposeRelationshipId</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentFormatCodeSets_CategoryPurposeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Main/PaymentFormatCodeSets_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentFormatCodeSets_W.cdm.json/PaymentFormatCodeSets_W</a></td><td><a href="../../Bank/Main/PaymentFormatCodeSets_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentFormatCodeSets_ChargeBearerRelationshipId name="Relationship_PaymentFormatCodeSets_ChargeBearerRelationshipId">Relationship_PaymentFormatCodeSets_ChargeBearerRelationshipId</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentFormatCodeSets_ChargeBearerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Main/PaymentFormatCodeSets_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentFormatCodeSets_W.cdm.json/PaymentFormatCodeSets_W</a></td><td><a href="../../Bank/Main/PaymentFormatCodeSets_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentFormatCodeSets_LocalInstrumentRelationshipId name="Relationship_PaymentFormatCodeSets_LocalInstrumentRelationshipId">Relationship_PaymentFormatCodeSets_LocalInstrumentRelationshipId</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentFormatCodeSets_LocalInstrumentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Main/PaymentFormatCodeSets_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentFormatCodeSets_W.cdm.json/PaymentFormatCodeSets_W</a></td><td><a href="../../Bank/Main/PaymentFormatCodeSets_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentFormatCodeSets_ServiceLevelRelationshipId name="Relationship_PaymentFormatCodeSets_ServiceLevelRelationshipId">Relationship_PaymentFormatCodeSets_ServiceLevelRelationshipId</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentFormatCodeSets_ServiceLevelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Main/PaymentFormatCodeSets_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentFormatCodeSets_W.cdm.json/PaymentFormatCodeSets_W</a></td><td><a href="../../Bank/Main/PaymentFormatCodeSets_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CashRegisterTerminal_WRelationshipId name="Relationship_CashRegisterTerminal_WRelationshipId">Relationship_CashRegisterTerminal_WRelationshipId</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CashRegisterTerminal_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountsReceivable/Main/CashRegisterTerminal_W.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Main/CashRegisterTerminal_W.cdm.json/CashRegisterTerminal_W</a></td><td><a href="../../AccountsReceivable/Main/CashRegisterTerminal_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CFDIWithholdingType_MXRelationshipId name="Relationship_CFDIWithholdingType_MXRelationshipId">Relationship_CFDIWithholdingType_MXRelationshipId</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CFDIWithholdingType_MXRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../EInvoice/Group/CFDIWithholdingType_MX.md" target="_blank">/core/operationsCommon/Tables/Finance/EInvoice/Group/CFDIWithholdingType_MX.cdm.json/CFDIWithholdingType_MX</a></td><td><a href="../../EInvoice/Group/CFDIWithholdingType_MX.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTransRelationshipId name="Relationship_CustTransRelationshipId">Relationship_CustTransRelationshipId</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTransRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_VendTransRelationshipId name="Relationship_VendTransRelationshipId">Relationship_VendTransRelationshipId</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTransRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/LedgerJournalTrans_W (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
