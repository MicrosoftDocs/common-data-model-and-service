---
title: AdvanceAdjustmentParameters_W - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Advance adjustment parameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/APARShared/Parameter/AdvanceAdjustmentParameters_W.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AdvanceAdjustmentParameters_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advance adjustment parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[CustPostingMode](#CustPostingMode)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[EmplPostingMode](#EmplPostingMode)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Ledger](#Ledger)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[LossCustLedgerDimension](#LossCustLedgerDimension)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[LossEmplLedgerDimension](#LossEmplLedgerDimension)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[LossVendLedgerDimension](#LossVendLedgerDimension)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[ProfitCustLedgerDimension](#ProfitCustLedgerDimension)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[ProfitEmplLedgerDimension](#ProfitEmplLedgerDimension)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[ProfitVendLedgerDimension](#ProfitVendLedgerDimension)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[RTax25CustLossLedgerDimension](#RTax25CustLossLedgerDimension)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[RTax25CustProfitLedgerDimension](#RTax25CustProfitLedgerDimension)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[RTax25EmplLossLedgerDimension](#RTax25EmplLossLedgerDimension)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[RTax25EmplProfitLedgerDimension](#RTax25EmplProfitLedgerDimension)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[RTax25OffsetLedgerDimensionCust](#RTax25OffsetLedgerDimensionCust)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[RTax25OffsetLedgerDimensionEmpl](#RTax25OffsetLedgerDimensionEmpl)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[RTax25OffsetLedgerDimensionVend](#RTax25OffsetLedgerDimensionVend)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[RTax25ProfitTableLossCust](#RTax25ProfitTableLossCust)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[RTax25ProfitTableLossEmpl](#RTax25ProfitTableLossEmpl)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[RTax25ProfitTableLossVend](#RTax25ProfitTableLossVend)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[RTax25ProfitTableProfitCust](#RTax25ProfitTableProfitCust)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[RTax25ProfitTableProfitEmpl](#RTax25ProfitTableProfitEmpl)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[RTax25ProfitTableProfitVend](#RTax25ProfitTableProfitVend)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[RTax25VendLossLedgerDimension](#RTax25VendLossLedgerDimension)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[RTax25VendProfitLedgerDimension](#RTax25VendProfitLedgerDimension)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[VATAdjustmentCust](#VATAdjustmentCust)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[VATAdjustmentLossCustLedgerDimension](#VATAdjustmentLossCustLedgerDimension)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[VATAdjustmentProfitCustLedgerDimension](#VATAdjustmentProfitCustLedgerDimension)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[VendPostingMode](#VendPostingMode)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_LedgerRelationshipId](#Relationship_LedgerRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_LossCustLedgerDimensionRelationshipId](#Relationship_LossCustLedgerDimensionRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_LossEmplLedgerDimensionRelationshipId](#Relationship_LossEmplLedgerDimensionRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_LossVendLedgerDimensionRelationshipId](#Relationship_LossVendLedgerDimensionRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_ProfitCustLedgerDimensionRelationshipId](#Relationship_ProfitCustLedgerDimensionRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_ProfitEmplLedgerDimensionRelationshipId](#Relationship_ProfitEmplLedgerDimensionRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_ProfitVendLedgerDimensionRelationshipId](#Relationship_ProfitVendLedgerDimensionRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_RTax25CustLossLedgerDimensionRelationshipId](#Relationship_RTax25CustLossLedgerDimensionRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_RTax25CustProfitLedgerDimensionRelationshipId](#Relationship_RTax25CustProfitLedgerDimensionRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_RTax25EmplLossLedgerDimensionRelationshipId](#Relationship_RTax25EmplLossLedgerDimensionRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_RTax25EmplProfitLedgerDimensionRelationshipId](#Relationship_RTax25EmplProfitLedgerDimensionRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_RTax25OffsetLedgerDimensionCustRelationshipId](#Relationship_RTax25OffsetLedgerDimensionCustRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_RTax25OffsetLedgerDimensionEmplRelationshipId](#Relationship_RTax25OffsetLedgerDimensionEmplRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_RTax25OffsetLedgerDimensionVendRelationshipId](#Relationship_RTax25OffsetLedgerDimensionVendRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_RTax25ProfitTableLossCustRelationshipId](#Relationship_RTax25ProfitTableLossCustRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_RTax25ProfitTableLossEmplRelationshipId](#Relationship_RTax25ProfitTableLossEmplRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_RTax25ProfitTableLossVendRelationshipId](#Relationship_RTax25ProfitTableLossVendRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_RTax25ProfitTableProfitCustRelationshipId](#Relationship_RTax25ProfitTableProfitCustRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_RTax25ProfitTableProfitEmplRelationshipId](#Relationship_RTax25ProfitTableProfitEmplRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_RTax25ProfitTableProfitVendRelationshipId](#Relationship_RTax25ProfitTableProfitVendRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_RTax25VendLossLedgerDimensionRelationshipId](#Relationship_RTax25VendLossLedgerDimensionRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_RTax25VendProfitLedgerDimensionRelationshipId](#Relationship_RTax25VendProfitLedgerDimensionRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_VATAdjustmentLossCustLedgerDimensionRelationshipId](#Relationship_VATAdjustmentLossCustLedgerDimensionRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|
|[Relationship_VATAdjustmentProfitCustLedgerDimensionRelationshipId](#Relationship_VATAdjustmentProfitCustLedgerDimensionRelationshipId)||<a href="AdvanceAdjustmentParameters_W.md" target="_blank">Parameter/AdvanceAdjustmentParameters_W</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AdvanceAdjustmentParameters_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustPostingMode name="CustPostingMode">CustPostingMode</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustPostingMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EmplPostingMode name="EmplPostingMode">EmplPostingMode</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmplPostingMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Ledger name="Ledger">Ledger</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ledger attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LossCustLedgerDimension name="LossCustLedgerDimension">LossCustLedgerDimension</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Realized loss</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LossCustLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Realized loss</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LossEmplLedgerDimension name="LossEmplLedgerDimension">LossEmplLedgerDimension</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Realized loss</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LossEmplLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Realized loss</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LossVendLedgerDimension name="LossVendLedgerDimension">LossVendLedgerDimension</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Realized loss</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LossVendLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Realized loss</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProfitCustLedgerDimension name="ProfitCustLedgerDimension">ProfitCustLedgerDimension</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Realized gain</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitCustLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Realized gain</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProfitEmplLedgerDimension name="ProfitEmplLedgerDimension">ProfitEmplLedgerDimension</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Realized gain</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitEmplLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Realized gain</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProfitVendLedgerDimension name="ProfitVendLedgerDimension">ProfitVendLedgerDimension</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Realized gain</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitVendLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Realized gain</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25CustLossLedgerDimension name="RTax25CustLossLedgerDimension">RTax25CustLossLedgerDimension</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Advance adjustment - loss</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25CustLossLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advance adjustment - loss</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25CustProfitLedgerDimension name="RTax25CustProfitLedgerDimension">RTax25CustProfitLedgerDimension</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Advance adjustment - profit</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25CustProfitLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advance adjustment - profit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25EmplLossLedgerDimension name="RTax25EmplLossLedgerDimension">RTax25EmplLossLedgerDimension</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Advance adjustment - loss</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25EmplLossLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advance adjustment - loss</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25EmplProfitLedgerDimension name="RTax25EmplProfitLedgerDimension">RTax25EmplProfitLedgerDimension</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Advance adjustment - profit</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25EmplProfitLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advance adjustment - profit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25OffsetLedgerDimensionCust name="RTax25OffsetLedgerDimensionCust">RTax25OffsetLedgerDimensionCust</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Advance adjustment offset account</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25OffsetLedgerDimensionCust attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advance adjustment offset account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25OffsetLedgerDimensionEmpl name="RTax25OffsetLedgerDimensionEmpl">RTax25OffsetLedgerDimensionEmpl</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Advance adjustment offset account</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25OffsetLedgerDimensionEmpl attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advance adjustment offset account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25OffsetLedgerDimensionVend name="RTax25OffsetLedgerDimensionVend">RTax25OffsetLedgerDimensionVend</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Advance adjustment offset account</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25OffsetLedgerDimensionVend attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advance adjustment offset account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableLossCust name="RTax25ProfitTableLossCust">RTax25ProfitTableLossCust</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableLossCust attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableLossEmpl name="RTax25ProfitTableLossEmpl">RTax25ProfitTableLossEmpl</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableLossEmpl attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableLossVend name="RTax25ProfitTableLossVend">RTax25ProfitTableLossVend</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableLossVend attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableProfitCust name="RTax25ProfitTableProfitCust">RTax25ProfitTableProfitCust</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableProfitCust attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableProfitEmpl name="RTax25ProfitTableProfitEmpl">RTax25ProfitTableProfitEmpl</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableProfitEmpl attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25ProfitTableProfitVend name="RTax25ProfitTableProfitVend">RTax25ProfitTableProfitVend</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTableProfitVend attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25VendLossLedgerDimension name="RTax25VendLossLedgerDimension">RTax25VendLossLedgerDimension</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Advance adjustment - loss</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25VendLossLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advance adjustment - loss</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25VendProfitLedgerDimension name="RTax25VendProfitLedgerDimension">RTax25VendProfitLedgerDimension</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Advance adjustment - profit</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25VendProfitLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advance adjustment - profit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VATAdjustmentCust name="VATAdjustmentCust">VATAdjustmentCust</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>VAT adjustment</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATAdjustmentCust attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>VAT adjustment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#VATAdjustmentLossCustLedgerDimension name="VATAdjustmentLossCustLedgerDimension">VATAdjustmentLossCustLedgerDimension</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Realized loss</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATAdjustmentLossCustLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Realized loss</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VATAdjustmentProfitCustLedgerDimension name="VATAdjustmentProfitCustLedgerDimension">VATAdjustmentProfitCustLedgerDimension</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Realized gain</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATAdjustmentProfitCustLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Realized gain</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VendPostingMode name="VendPostingMode">VendPostingMode</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendPostingMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_LedgerRelationshipId name="Relationship_LedgerRelationshipId">Relationship_LedgerRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/Ledger.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/Ledger.cdm.json/Ledger</a></td><td><a href="../../Ledger/Main/Ledger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LossCustLedgerDimensionRelationshipId name="Relationship_LossCustLedgerDimensionRelationshipId">Relationship_LossCustLedgerDimensionRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LossCustLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LossEmplLedgerDimensionRelationshipId name="Relationship_LossEmplLedgerDimensionRelationshipId">Relationship_LossEmplLedgerDimensionRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LossEmplLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LossVendLedgerDimensionRelationshipId name="Relationship_LossVendLedgerDimensionRelationshipId">Relationship_LossVendLedgerDimensionRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LossVendLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProfitCustLedgerDimensionRelationshipId name="Relationship_ProfitCustLedgerDimensionRelationshipId">Relationship_ProfitCustLedgerDimensionRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProfitCustLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProfitEmplLedgerDimensionRelationshipId name="Relationship_ProfitEmplLedgerDimensionRelationshipId">Relationship_ProfitEmplLedgerDimensionRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProfitEmplLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProfitVendLedgerDimensionRelationshipId name="Relationship_ProfitVendLedgerDimensionRelationshipId">Relationship_ProfitVendLedgerDimensionRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProfitVendLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25CustLossLedgerDimensionRelationshipId name="Relationship_RTax25CustLossLedgerDimensionRelationshipId">Relationship_RTax25CustLossLedgerDimensionRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25CustLossLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25CustProfitLedgerDimensionRelationshipId name="Relationship_RTax25CustProfitLedgerDimensionRelationshipId">Relationship_RTax25CustProfitLedgerDimensionRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25CustProfitLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25EmplLossLedgerDimensionRelationshipId name="Relationship_RTax25EmplLossLedgerDimensionRelationshipId">Relationship_RTax25EmplLossLedgerDimensionRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25EmplLossLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25EmplProfitLedgerDimensionRelationshipId name="Relationship_RTax25EmplProfitLedgerDimensionRelationshipId">Relationship_RTax25EmplProfitLedgerDimensionRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25EmplProfitLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25OffsetLedgerDimensionCustRelationshipId name="Relationship_RTax25OffsetLedgerDimensionCustRelationshipId">Relationship_RTax25OffsetLedgerDimensionCustRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25OffsetLedgerDimensionCustRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25OffsetLedgerDimensionEmplRelationshipId name="Relationship_RTax25OffsetLedgerDimensionEmplRelationshipId">Relationship_RTax25OffsetLedgerDimensionEmplRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25OffsetLedgerDimensionEmplRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25OffsetLedgerDimensionVendRelationshipId name="Relationship_RTax25OffsetLedgerDimensionVendRelationshipId">Relationship_RTax25OffsetLedgerDimensionVendRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25OffsetLedgerDimensionVendRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableLossCustRelationshipId name="Relationship_RTax25ProfitTableLossCustRelationshipId">Relationship_RTax25ProfitTableLossCustRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableLossCustRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableLossEmplRelationshipId name="Relationship_RTax25ProfitTableLossEmplRelationshipId">Relationship_RTax25ProfitTableLossEmplRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableLossEmplRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableLossVendRelationshipId name="Relationship_RTax25ProfitTableLossVendRelationshipId">Relationship_RTax25ProfitTableLossVendRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableLossVendRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableProfitCustRelationshipId name="Relationship_RTax25ProfitTableProfitCustRelationshipId">Relationship_RTax25ProfitTableProfitCustRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableProfitCustRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableProfitEmplRelationshipId name="Relationship_RTax25ProfitTableProfitEmplRelationshipId">Relationship_RTax25ProfitTableProfitEmplRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableProfitEmplRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableProfitVendRelationshipId name="Relationship_RTax25ProfitTableProfitVendRelationshipId">Relationship_RTax25ProfitTableProfitVendRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableProfitVendRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Group/RTax25ProfitTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../../RTax25/Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25VendLossLedgerDimensionRelationshipId name="Relationship_RTax25VendLossLedgerDimensionRelationshipId">Relationship_RTax25VendLossLedgerDimensionRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25VendLossLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25VendProfitLedgerDimensionRelationshipId name="Relationship_RTax25VendProfitLedgerDimensionRelationshipId">Relationship_RTax25VendProfitLedgerDimensionRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25VendProfitLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VATAdjustmentLossCustLedgerDimensionRelationshipId name="Relationship_VATAdjustmentLossCustLedgerDimensionRelationshipId">Relationship_VATAdjustmentLossCustLedgerDimensionRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VATAdjustmentLossCustLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VATAdjustmentProfitCustLedgerDimensionRelationshipId name="Relationship_VATAdjustmentProfitCustLedgerDimensionRelationshipId">Relationship_VATAdjustmentProfitCustLedgerDimensionRelationshipId</a>

First included in: Parameter/AdvanceAdjustmentParameters_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VATAdjustmentProfitCustLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
