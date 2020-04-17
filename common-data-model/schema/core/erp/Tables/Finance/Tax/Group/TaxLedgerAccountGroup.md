---
title: TaxLedgerAccountGroup - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# TaxLedgerAccountGroup

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/Tax/Group/TaxLedgerAccountGroup.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxLedgerAccountGroup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[CashDiscountIncomingLedgerDimension](#CashDiscountIncomingLedgerDimension)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[CashDiscountOutgoingLedgerDimension](#CashDiscountOutgoingLedgerDimension)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Name](#Name)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[PennyDifferenceCustomerLedgerDimension](#PennyDifferenceCustomerLedgerDimension)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[PennyDifferenceVendorLedgerDimension](#PennyDifferenceVendorLedgerDimension)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxAccountGroup](#TaxAccountGroup)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxAccountVatInAdvance_IT](#TaxAccountVatInAdvance_IT)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxDeferredLedgerDimension_RU](#TaxDeferredLedgerDimension_RU)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxFineLedgerDimension_RU](#TaxFineLedgerDimension_RU)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxFreePercentLedgerDimension](#TaxFreePercentLedgerDimension)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxGoodsInRouteLedgerDimension_RU](#TaxGoodsInRouteLedgerDimension_RU)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxIncomingDeferredLedgerDimension_HU](#TaxIncomingDeferredLedgerDimension_HU)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxIncomingDifferenceLedgerDimension](#TaxIncomingDifferenceLedgerDimension)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxIncomingDiffOffsetLedgerDimension](#TaxIncomingDiffOffsetLedgerDimension)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxIncomingLedgerDimension](#TaxIncomingLedgerDimension)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxIncomingLongTermLedgerDimension_BR](#TaxIncomingLongTermLedgerDimension_BR)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxIncomingPaymentLedgerDimension_RU](#TaxIncomingPaymentLedgerDimension_RU)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxIncomingShortTermLedgerDimension_BR](#TaxIncomingShortTermLedgerDimension_BR)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxOffsetUseTaxLedgerDimension](#TaxOffsetUseTaxLedgerDimension)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxOutgoingDeferredLedgerDimension_HU](#TaxOutgoingDeferredLedgerDimension_HU)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxOutgoingDifferenceLedgerDimension](#TaxOutgoingDifferenceLedgerDimension)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxOutgoingDiffOffsetLedgerDimension](#TaxOutgoingDiffOffsetLedgerDimension)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxOutgoingLedgerDimension](#TaxOutgoingLedgerDimension)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxOutgoingOffsetLedgerDimension_RU](#TaxOutgoingOffsetLedgerDimension_RU)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxReportLedgerDimension](#TaxReportLedgerDimension)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxReverseOffsetIncLedgerDimension_W](#TaxReverseOffsetIncLedgerDimension_W)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxReverseOffsetOutLedgerDimension_W](#TaxReverseOffsetOutLedgerDimension_W)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxSalesOffsetLedgerDimension_BR](#TaxSalesOffsetLedgerDimension_BR)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxUnrealizedPayablesLedgerDimension](#TaxUnrealizedPayablesLedgerDimension)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxUnrealizedReceivablesLedgerDimension](#TaxUnrealizedReceivablesLedgerDimension)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxUseTaxLedgerDimension](#TaxUseTaxLedgerDimension)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[TaxVatInAdvanceLedgerDimension_IT](#TaxVatInAdvanceLedgerDimension_IT)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_CashDiscountIncomingLedgerDimensionRelationshipId](#Relationship_CashDiscountIncomingLedgerDimensionRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_CashDiscountOutgoingLedgerDimensionRelationshipId](#Relationship_CashDiscountOutgoingLedgerDimensionRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_PennyDifferenceCustomerLedgerDimensionRelationshipId](#Relationship_PennyDifferenceCustomerLedgerDimensionRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_PennyDifferenceVendorLedgerDimensionRelationshipId](#Relationship_PennyDifferenceVendorLedgerDimensionRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxDeferredLedgerDimension_RURelationshipId](#Relationship_TaxDeferredLedgerDimension_RURelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxFineLedgerDimension_RURelationshipId](#Relationship_TaxFineLedgerDimension_RURelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxFreePercentLedgerDimensionRelationshipId](#Relationship_TaxFreePercentLedgerDimensionRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxGoodsInRouteLedgerDimension_RURelationshipId](#Relationship_TaxGoodsInRouteLedgerDimension_RURelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxIncomingDeferredLedgerDimension_HURelationshipId](#Relationship_TaxIncomingDeferredLedgerDimension_HURelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxIncomingDifferenceLedgerDimensionRelationshipId](#Relationship_TaxIncomingDifferenceLedgerDimensionRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxIncomingDifferenceOffsetLedgerDimRelationshipId](#Relationship_TaxIncomingDifferenceOffsetLedgerDimRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxIncomingLedgerDimensionRelationshipId](#Relationship_TaxIncomingLedgerDimensionRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxIncomingLongTermLedgerDimension_BRRelationshipId](#Relationship_TaxIncomingLongTermLedgerDimension_BRRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxIncomingPaymentLedgerDimension_RURelationshipId](#Relationship_TaxIncomingPaymentLedgerDimension_RURelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxIncomingShortTermLedgerDimension_BRRelationshipId](#Relationship_TaxIncomingShortTermLedgerDimension_BRRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxOffsetUseTaxLedgerDimensionRelationshipId](#Relationship_TaxOffsetUseTaxLedgerDimensionRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxOutgoingDeferredLedgerDimension_HURelationshipId](#Relationship_TaxOutgoingDeferredLedgerDimension_HURelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxOutgoingDifferenceLedgerDimensionRelationshipId](#Relationship_TaxOutgoingDifferenceLedgerDimensionRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxOutgoingDifferenceOffsetLedgerDimRelationshipId](#Relationship_TaxOutgoingDifferenceOffsetLedgerDimRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxOutgoingLedgerDimensionRelationshipId](#Relationship_TaxOutgoingLedgerDimensionRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxOutgoingOffsetLedgerDimension_RURelationshipId](#Relationship_TaxOutgoingOffsetLedgerDimension_RURelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxReportLedgerDimensionRelationshipId](#Relationship_TaxReportLedgerDimensionRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxReverseOffsetIncLedgerDimension_WRelationshipId](#Relationship_TaxReverseOffsetIncLedgerDimension_WRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxReverseOffsetOutLedgerDimension_WRelationshipId](#Relationship_TaxReverseOffsetOutLedgerDimension_WRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxSalesOffsetLedgerDimension_BRRelationshipId](#Relationship_TaxSalesOffsetLedgerDimension_BRRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxUnrealizedPayablesLedgerDimensionRelationshipId](#Relationship_TaxUnrealizedPayablesLedgerDimensionRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxUnrealizedReceivablesLedgerDimensionRelationshipId](#Relationship_TaxUnrealizedReceivablesLedgerDimensionRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxUseTaxLedgerDimensionRelationshipId](#Relationship_TaxUseTaxLedgerDimensionRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_TaxVatInAdvanceLedgerDimension_ITRelationshipId](#Relationship_TaxVatInAdvanceLedgerDimension_ITRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxLedgerAccountGroup.md" target="_blank">Group/TaxLedgerAccountGroup</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxLedgerAccountGroup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CashDiscountIncomingLedgerDimension name="CashDiscountIncomingLedgerDimension">CashDiscountIncomingLedgerDimension</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountIncomingLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CashDiscountOutgoingLedgerDimension name="CashDiscountOutgoingLedgerDimension">CashDiscountOutgoingLedgerDimension</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountOutgoingLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

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

### <a href=#PennyDifferenceCustomerLedgerDimension name="PennyDifferenceCustomerLedgerDimension">PennyDifferenceCustomerLedgerDimension</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PennyDifferenceCustomerLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PennyDifferenceVendorLedgerDimension name="PennyDifferenceVendorLedgerDimension">PennyDifferenceVendorLedgerDimension</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PennyDifferenceVendorLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxAccountGroup name="TaxAccountGroup">TaxAccountGroup</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAccountGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAccountVatInAdvance_IT name="TaxAccountVatInAdvance_IT">TaxAccountVatInAdvance_IT</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAccountVatInAdvance_IT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxDeferredLedgerDimension_RU name="TaxDeferredLedgerDimension_RU">TaxDeferredLedgerDimension_RU</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxDeferredLedgerDimension_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxFineLedgerDimension_RU name="TaxFineLedgerDimension_RU">TaxFineLedgerDimension_RU</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxFineLedgerDimension_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxFreePercentLedgerDimension name="TaxFreePercentLedgerDimension">TaxFreePercentLedgerDimension</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxFreePercentLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxGoodsInRouteLedgerDimension_RU name="TaxGoodsInRouteLedgerDimension_RU">TaxGoodsInRouteLedgerDimension_RU</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGoodsInRouteLedgerDimension_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxIncomingDeferredLedgerDimension_HU name="TaxIncomingDeferredLedgerDimension_HU">TaxIncomingDeferredLedgerDimension_HU</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIncomingDeferredLedgerDimension_HU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxIncomingDifferenceLedgerDimension name="TaxIncomingDifferenceLedgerDimension">TaxIncomingDifferenceLedgerDimension</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIncomingDifferenceLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxIncomingDiffOffsetLedgerDimension name="TaxIncomingDiffOffsetLedgerDimension">TaxIncomingDiffOffsetLedgerDimension</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIncomingDiffOffsetLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxIncomingLedgerDimension name="TaxIncomingLedgerDimension">TaxIncomingLedgerDimension</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIncomingLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxIncomingLongTermLedgerDimension_BR name="TaxIncomingLongTermLedgerDimension_BR">TaxIncomingLongTermLedgerDimension_BR</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIncomingLongTermLedgerDimension_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxIncomingPaymentLedgerDimension_RU name="TaxIncomingPaymentLedgerDimension_RU">TaxIncomingPaymentLedgerDimension_RU</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIncomingPaymentLedgerDimension_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxIncomingShortTermLedgerDimension_BR name="TaxIncomingShortTermLedgerDimension_BR">TaxIncomingShortTermLedgerDimension_BR</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIncomingShortTermLedgerDimension_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxOffsetUseTaxLedgerDimension name="TaxOffsetUseTaxLedgerDimension">TaxOffsetUseTaxLedgerDimension</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOffsetUseTaxLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxOutgoingDeferredLedgerDimension_HU name="TaxOutgoingDeferredLedgerDimension_HU">TaxOutgoingDeferredLedgerDimension_HU</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOutgoingDeferredLedgerDimension_HU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxOutgoingDifferenceLedgerDimension name="TaxOutgoingDifferenceLedgerDimension">TaxOutgoingDifferenceLedgerDimension</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOutgoingDifferenceLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxOutgoingDiffOffsetLedgerDimension name="TaxOutgoingDiffOffsetLedgerDimension">TaxOutgoingDiffOffsetLedgerDimension</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOutgoingDiffOffsetLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxOutgoingLedgerDimension name="TaxOutgoingLedgerDimension">TaxOutgoingLedgerDimension</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOutgoingLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxOutgoingOffsetLedgerDimension_RU name="TaxOutgoingOffsetLedgerDimension_RU">TaxOutgoingOffsetLedgerDimension_RU</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOutgoingOffsetLedgerDimension_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxReportLedgerDimension name="TaxReportLedgerDimension">TaxReportLedgerDimension</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReportLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxReverseOffsetIncLedgerDimension_W name="TaxReverseOffsetIncLedgerDimension_W">TaxReverseOffsetIncLedgerDimension_W</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReverseOffsetIncLedgerDimension_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxReverseOffsetOutLedgerDimension_W name="TaxReverseOffsetOutLedgerDimension_W">TaxReverseOffsetOutLedgerDimension_W</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReverseOffsetOutLedgerDimension_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxSalesOffsetLedgerDimension_BR name="TaxSalesOffsetLedgerDimension_BR">TaxSalesOffsetLedgerDimension_BR</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSalesOffsetLedgerDimension_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxUnrealizedPayablesLedgerDimension name="TaxUnrealizedPayablesLedgerDimension">TaxUnrealizedPayablesLedgerDimension</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxUnrealizedPayablesLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxUnrealizedReceivablesLedgerDimension name="TaxUnrealizedReceivablesLedgerDimension">TaxUnrealizedReceivablesLedgerDimension</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxUnrealizedReceivablesLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxUseTaxLedgerDimension name="TaxUseTaxLedgerDimension">TaxUseTaxLedgerDimension</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxUseTaxLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxVatInAdvanceLedgerDimension_IT name="TaxVatInAdvanceLedgerDimension_IT">TaxVatInAdvanceLedgerDimension_IT</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxVatInAdvanceLedgerDimension_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

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

### <a href=#Relationship_CashDiscountIncomingLedgerDimensionRelationshipId name="Relationship_CashDiscountIncomingLedgerDimensionRelationshipId">Relationship_CashDiscountIncomingLedgerDimensionRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CashDiscountIncomingLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CashDiscountOutgoingLedgerDimensionRelationshipId name="Relationship_CashDiscountOutgoingLedgerDimensionRelationshipId">Relationship_CashDiscountOutgoingLedgerDimensionRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CashDiscountOutgoingLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PennyDifferenceCustomerLedgerDimensionRelationshipId name="Relationship_PennyDifferenceCustomerLedgerDimensionRelationshipId">Relationship_PennyDifferenceCustomerLedgerDimensionRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PennyDifferenceCustomerLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PennyDifferenceVendorLedgerDimensionRelationshipId name="Relationship_PennyDifferenceVendorLedgerDimensionRelationshipId">Relationship_PennyDifferenceVendorLedgerDimensionRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PennyDifferenceVendorLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxDeferredLedgerDimension_RURelationshipId name="Relationship_TaxDeferredLedgerDimension_RURelationshipId">Relationship_TaxDeferredLedgerDimension_RURelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxDeferredLedgerDimension_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxFineLedgerDimension_RURelationshipId name="Relationship_TaxFineLedgerDimension_RURelationshipId">Relationship_TaxFineLedgerDimension_RURelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxFineLedgerDimension_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxFreePercentLedgerDimensionRelationshipId name="Relationship_TaxFreePercentLedgerDimensionRelationshipId">Relationship_TaxFreePercentLedgerDimensionRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxFreePercentLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxGoodsInRouteLedgerDimension_RURelationshipId name="Relationship_TaxGoodsInRouteLedgerDimension_RURelationshipId">Relationship_TaxGoodsInRouteLedgerDimension_RURelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxGoodsInRouteLedgerDimension_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxIncomingDeferredLedgerDimension_HURelationshipId name="Relationship_TaxIncomingDeferredLedgerDimension_HURelationshipId">Relationship_TaxIncomingDeferredLedgerDimension_HURelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxIncomingDeferredLedgerDimension_HURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxIncomingDifferenceLedgerDimensionRelationshipId name="Relationship_TaxIncomingDifferenceLedgerDimensionRelationshipId">Relationship_TaxIncomingDifferenceLedgerDimensionRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxIncomingDifferenceLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxIncomingDifferenceOffsetLedgerDimRelationshipId name="Relationship_TaxIncomingDifferenceOffsetLedgerDimRelationshipId">Relationship_TaxIncomingDifferenceOffsetLedgerDimRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxIncomingDifferenceOffsetLedgerDimRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxIncomingLedgerDimensionRelationshipId name="Relationship_TaxIncomingLedgerDimensionRelationshipId">Relationship_TaxIncomingLedgerDimensionRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxIncomingLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxIncomingLongTermLedgerDimension_BRRelationshipId name="Relationship_TaxIncomingLongTermLedgerDimension_BRRelationshipId">Relationship_TaxIncomingLongTermLedgerDimension_BRRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxIncomingLongTermLedgerDimension_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxIncomingPaymentLedgerDimension_RURelationshipId name="Relationship_TaxIncomingPaymentLedgerDimension_RURelationshipId">Relationship_TaxIncomingPaymentLedgerDimension_RURelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxIncomingPaymentLedgerDimension_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxIncomingShortTermLedgerDimension_BRRelationshipId name="Relationship_TaxIncomingShortTermLedgerDimension_BRRelationshipId">Relationship_TaxIncomingShortTermLedgerDimension_BRRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxIncomingShortTermLedgerDimension_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxOffsetUseTaxLedgerDimensionRelationshipId name="Relationship_TaxOffsetUseTaxLedgerDimensionRelationshipId">Relationship_TaxOffsetUseTaxLedgerDimensionRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxOffsetUseTaxLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxOutgoingDeferredLedgerDimension_HURelationshipId name="Relationship_TaxOutgoingDeferredLedgerDimension_HURelationshipId">Relationship_TaxOutgoingDeferredLedgerDimension_HURelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxOutgoingDeferredLedgerDimension_HURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxOutgoingDifferenceLedgerDimensionRelationshipId name="Relationship_TaxOutgoingDifferenceLedgerDimensionRelationshipId">Relationship_TaxOutgoingDifferenceLedgerDimensionRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxOutgoingDifferenceLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxOutgoingDifferenceOffsetLedgerDimRelationshipId name="Relationship_TaxOutgoingDifferenceOffsetLedgerDimRelationshipId">Relationship_TaxOutgoingDifferenceOffsetLedgerDimRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxOutgoingDifferenceOffsetLedgerDimRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxOutgoingLedgerDimensionRelationshipId name="Relationship_TaxOutgoingLedgerDimensionRelationshipId">Relationship_TaxOutgoingLedgerDimensionRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxOutgoingLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxOutgoingOffsetLedgerDimension_RURelationshipId name="Relationship_TaxOutgoingOffsetLedgerDimension_RURelationshipId">Relationship_TaxOutgoingOffsetLedgerDimension_RURelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxOutgoingOffsetLedgerDimension_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportLedgerDimensionRelationshipId name="Relationship_TaxReportLedgerDimensionRelationshipId">Relationship_TaxReportLedgerDimensionRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReverseOffsetIncLedgerDimension_WRelationshipId name="Relationship_TaxReverseOffsetIncLedgerDimension_WRelationshipId">Relationship_TaxReverseOffsetIncLedgerDimension_WRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReverseOffsetIncLedgerDimension_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReverseOffsetOutLedgerDimension_WRelationshipId name="Relationship_TaxReverseOffsetOutLedgerDimension_WRelationshipId">Relationship_TaxReverseOffsetOutLedgerDimension_WRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReverseOffsetOutLedgerDimension_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxSalesOffsetLedgerDimension_BRRelationshipId name="Relationship_TaxSalesOffsetLedgerDimension_BRRelationshipId">Relationship_TaxSalesOffsetLedgerDimension_BRRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxSalesOffsetLedgerDimension_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxUnrealizedPayablesLedgerDimensionRelationshipId name="Relationship_TaxUnrealizedPayablesLedgerDimensionRelationshipId">Relationship_TaxUnrealizedPayablesLedgerDimensionRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxUnrealizedPayablesLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxUnrealizedReceivablesLedgerDimensionRelationshipId name="Relationship_TaxUnrealizedReceivablesLedgerDimensionRelationshipId">Relationship_TaxUnrealizedReceivablesLedgerDimensionRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxUnrealizedReceivablesLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxUseTaxLedgerDimensionRelationshipId name="Relationship_TaxUseTaxLedgerDimensionRelationshipId">Relationship_TaxUseTaxLedgerDimensionRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxUseTaxLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxVatInAdvanceLedgerDimension_ITRelationshipId name="Relationship_TaxVatInAdvanceLedgerDimension_ITRelationshipId">Relationship_TaxVatInAdvanceLedgerDimension_ITRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxVatInAdvanceLedgerDimension_ITRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/TaxLedgerAccountGroup (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
