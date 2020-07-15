---
title: PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Purchase order creation and demand consolidation policies in ProcurementAndSourcing(PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase order creation and demand consolidation policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Policy](#Policy)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[PolicyRuleType](#PolicyRuleType)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[ValidFrom](#ValidFrom)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[ValidTo](#ValidTo)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[IsPriceDiscountTransferRuleOverrideAllowed](#IsPriceDiscountTransferRuleOverrideAllowed)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[PurchaseRequisitionPriceToleranceErrorProcessingRule](#PurchaseRequisitionPriceToleranceErrorProcessingRule)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[IsAutomaticPurchaseOrderCreationBatchJobEnabled](#IsAutomaticPurchaseOrderCreationBatchJobEnabled)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[PurchaseRequisitionPriceDiscountTransferRule](#PurchaseRequisitionPriceDiscountTransferRule)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[PurchaseOrderLineProductDescriptionTransferRule](#PurchaseOrderLineProductDescriptionTransferRule)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[PolicyRuleName](#PolicyRuleName)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[PurchasingPolicyName](#PurchasingPolicyName)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[PurchaseReqInternalCatalogItemMaximumPriceToleranceAmount](#PurchaseReqInternalCatalogItemMaximumPriceToleranceAmount)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[PurchaseReqInternalCatalogItemMaximumPriceToleranceAmountCurrencyCode](#PurchaseReqInternalCatalogItemMaximumPriceToleranceAmountCurrencyCode)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[IsPurchaseRequisitionInternalCatalogItemMaximumPriceToleranceAmountEnabled](#IsPurchaseRequisitionInternalCatalogItemMaximumPriceToleranceAmountEnabled)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[IsPurchaseRequisitionInternalCatalogItemMaximumPriceTolerancePercentageEnabled](#IsPurchaseRequisitionInternalCatalogItemMaximumPriceTolerancePercentageEnabled)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[EnablePriceTolerance](#EnablePriceTolerance)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[PurchaseRequisitionInternalCatalogItemMaximumPriceTolerancePercentage](#PurchaseRequisitionInternalCatalogItemMaximumPriceTolerancePercentage)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[ArePurchaseOrdersRequisitionLineTypeSpecific](#ArePurchaseOrdersRequisitionLineTypeSpecific)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[ArePurchaseOrdersRequisitionProcurementProductCategorySpecific](#ArePurchaseOrdersRequisitionProcurementProductCategorySpecific)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[ArePurchaseOrdersRequisitionRequesterSpecific](#ArePurchaseOrdersRequisitionRequesterSpecific)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[PurchaseOrderCreationExternalCatalogItemExceptionRule](#PurchaseOrderCreationExternalCatalogItemExceptionRule)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[PurchaseOrderCreationInternalCatalogItemExceptionRule](#PurchaseOrderCreationInternalCatalogItemExceptionRule)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[PurchaseOrderCreationNonCatalogItemExceptionRule](#PurchaseOrderCreationNonCatalogItemExceptionRule)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[WillAutomaticPurchaseOrderCreationExcludePrepaidPurchaseRequisitionLines](#WillAutomaticPurchaseOrderCreationExcludePrepaidPurchaseRequisitionLines)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[ManualPurchaseOrderCreationRule](#ManualPurchaseOrderCreationRule)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[WillPurchaseRequisitionApprovalMergeVendorFinancialDimensions](#WillPurchaseRequisitionApprovalMergeVendorFinancialDimensions)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[DemandConsolidationExternalCatalogItemExceptionRule](#DemandConsolidationExternalCatalogItemExceptionRule)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[DemandConsolidationInternalCatalogItemExceptionRule](#DemandConsolidationInternalCatalogItemExceptionRule)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[DemandConsolidationNonCatalogItemExceptionRule](#DemandConsolidationNonCatalogItemExceptionRule)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[DemandConsolidationRule](#DemandConsolidationRule)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|
|[BackingTable_PurchReqSourcingPolicyRuleRelationshipId](#BackingTable_PurchReqSourcingPolicyRuleRelationshipId)||<a href="PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity</a>|

### <a href=#Policy name="Policy">Policy</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Policy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyRuleType name="PolicyRuleType">PolicyRuleType</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRuleType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPriceDiscountTransferRuleOverrideAllowed name="IsPriceDiscountTransferRuleOverrideAllowed">IsPriceDiscountTransferRuleOverrideAllowed</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPriceDiscountTransferRuleOverrideAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseRequisitionPriceToleranceErrorProcessingRule name="PurchaseRequisitionPriceToleranceErrorProcessingRule">PurchaseRequisitionPriceToleranceErrorProcessingRule</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseRequisitionPriceToleranceErrorProcessingRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAutomaticPurchaseOrderCreationBatchJobEnabled name="IsAutomaticPurchaseOrderCreationBatchJobEnabled">IsAutomaticPurchaseOrderCreationBatchJobEnabled</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAutomaticPurchaseOrderCreationBatchJobEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseRequisitionPriceDiscountTransferRule name="PurchaseRequisitionPriceDiscountTransferRule">PurchaseRequisitionPriceDiscountTransferRule</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseRequisitionPriceDiscountTransferRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderLineProductDescriptionTransferRule name="PurchaseOrderLineProductDescriptionTransferRule">PurchaseOrderLineProductDescriptionTransferRule</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderLineProductDescriptionTransferRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyRuleName name="PolicyRuleName">PolicyRuleName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRuleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasingPolicyName name="PurchasingPolicyName">PurchasingPolicyName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasingPolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseReqInternalCatalogItemMaximumPriceToleranceAmount name="PurchaseReqInternalCatalogItemMaximumPriceToleranceAmount">PurchaseReqInternalCatalogItemMaximumPriceToleranceAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseReqInternalCatalogItemMaximumPriceToleranceAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseReqInternalCatalogItemMaximumPriceToleranceAmountCurrencyCode name="PurchaseReqInternalCatalogItemMaximumPriceToleranceAmountCurrencyCode">PurchaseReqInternalCatalogItemMaximumPriceToleranceAmountCurrencyCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseReqInternalCatalogItemMaximumPriceToleranceAmountCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPurchaseRequisitionInternalCatalogItemMaximumPriceToleranceAmountEnabled name="IsPurchaseRequisitionInternalCatalogItemMaximumPriceToleranceAmountEnabled">IsPurchaseRequisitionInternalCatalogItemMaximumPriceToleranceAmountEnabled</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchaseRequisitionInternalCatalogItemMaximumPriceToleranceAmountEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPurchaseRequisitionInternalCatalogItemMaximumPriceTolerancePercentageEnabled name="IsPurchaseRequisitionInternalCatalogItemMaximumPriceTolerancePercentageEnabled">IsPurchaseRequisitionInternalCatalogItemMaximumPriceTolerancePercentageEnabled</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchaseRequisitionInternalCatalogItemMaximumPriceTolerancePercentageEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnablePriceTolerance name="EnablePriceTolerance">EnablePriceTolerance</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnablePriceTolerance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseRequisitionInternalCatalogItemMaximumPriceTolerancePercentage name="PurchaseRequisitionInternalCatalogItemMaximumPriceTolerancePercentage">PurchaseRequisitionInternalCatalogItemMaximumPriceTolerancePercentage</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseRequisitionInternalCatalogItemMaximumPriceTolerancePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePurchaseOrdersRequisitionLineTypeSpecific name="ArePurchaseOrdersRequisitionLineTypeSpecific">ArePurchaseOrdersRequisitionLineTypeSpecific</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePurchaseOrdersRequisitionLineTypeSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePurchaseOrdersRequisitionProcurementProductCategorySpecific name="ArePurchaseOrdersRequisitionProcurementProductCategorySpecific">ArePurchaseOrdersRequisitionProcurementProductCategorySpecific</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePurchaseOrdersRequisitionProcurementProductCategorySpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ArePurchaseOrdersRequisitionRequesterSpecific name="ArePurchaseOrdersRequisitionRequesterSpecific">ArePurchaseOrdersRequisitionRequesterSpecific</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePurchaseOrdersRequisitionRequesterSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderCreationExternalCatalogItemExceptionRule name="PurchaseOrderCreationExternalCatalogItemExceptionRule">PurchaseOrderCreationExternalCatalogItemExceptionRule</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderCreationExternalCatalogItemExceptionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderCreationInternalCatalogItemExceptionRule name="PurchaseOrderCreationInternalCatalogItemExceptionRule">PurchaseOrderCreationInternalCatalogItemExceptionRule</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderCreationInternalCatalogItemExceptionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderCreationNonCatalogItemExceptionRule name="PurchaseOrderCreationNonCatalogItemExceptionRule">PurchaseOrderCreationNonCatalogItemExceptionRule</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderCreationNonCatalogItemExceptionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillAutomaticPurchaseOrderCreationExcludePrepaidPurchaseRequisitionLines name="WillAutomaticPurchaseOrderCreationExcludePrepaidPurchaseRequisitionLines">WillAutomaticPurchaseOrderCreationExcludePrepaidPurchaseRequisitionLines</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillAutomaticPurchaseOrderCreationExcludePrepaidPurchaseRequisitionLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManualPurchaseOrderCreationRule name="ManualPurchaseOrderCreationRule">ManualPurchaseOrderCreationRule</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualPurchaseOrderCreationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPurchaseRequisitionApprovalMergeVendorFinancialDimensions name="WillPurchaseRequisitionApprovalMergeVendorFinancialDimensions">WillPurchaseRequisitionApprovalMergeVendorFinancialDimensions</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPurchaseRequisitionApprovalMergeVendorFinancialDimensions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandConsolidationExternalCatalogItemExceptionRule name="DemandConsolidationExternalCatalogItemExceptionRule">DemandConsolidationExternalCatalogItemExceptionRule</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandConsolidationExternalCatalogItemExceptionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandConsolidationInternalCatalogItemExceptionRule name="DemandConsolidationInternalCatalogItemExceptionRule">DemandConsolidationInternalCatalogItemExceptionRule</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandConsolidationInternalCatalogItemExceptionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandConsolidationNonCatalogItemExceptionRule name="DemandConsolidationNonCatalogItemExceptionRule">DemandConsolidationNonCatalogItemExceptionRule</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandConsolidationNonCatalogItemExceptionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandConsolidationRule name="DemandConsolidationRule">DemandConsolidationRule</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandConsolidationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PurchReqSourcingPolicyRuleRelationshipId name="BackingTable_PurchReqSourcingPolicyRuleRelationshipId">BackingTable_PurchReqSourcingPolicyRuleRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderCreationAndDemandConsolidationPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchReqSourcingPolicyRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchReqSourcingPolicyRule.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchReqSourcingPolicyRule.cdm.json/PurchReqSourcingPolicyRule</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchReqSourcingPolicyRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
