---
title: IntercompanyTradingPartnershipProcurementPolicyEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Intercompany procurement policies in ProcurementAndSourcing(IntercompanyTradingPartnershipProcurementPolicyEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Intercompany procurement policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[VendorLegalEntityId](#VendorLegalEntityId)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsDirectDeliveryOriginalSalesOrderPackingSlipAutomaticallyPrinted](#IsDirectDeliveryOriginalSalesOrderPackingSlipAutomaticallyPrinted)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsDirectDeliveryOriginalSalesOrderInvoiceAutomaticallyPosted](#IsDirectDeliveryOriginalSalesOrderInvoiceAutomaticallyPosted)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsDirectDeliveryOriginalSalesOrderInvoiceAutomaticallyPrinted](#IsDirectDeliveryOriginalSalesOrderInvoiceAutomaticallyPrinted)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsDirectDeliveryIntercompanyPurchaseOrderProductReceiptAutomaticallyPrinted](#IsDirectDeliveryIntercompanyPurchaseOrderProductReceiptAutomaticallyPrinted)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsDirectDeliveryIntercompanyPurchaseOrderInvoiceAutomaticallyPosted](#IsDirectDeliveryIntercompanyPurchaseOrderInvoiceAutomaticallyPosted)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsDirectDeliveryIntercompanyPurchaseOrderInvoiceAutomaticallyPrinted](#IsDirectDeliveryIntercompanyPurchaseOrderInvoiceAutomaticallyPrinted)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[FixedChargeAllocationMethod](#FixedChargeAllocationMethod)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsOnlyStockedProductAllocatedFixedCharge](#IsOnlyStockedProductAllocatedFixedCharge)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsIntercompayPurchaseOrderCreationUsingPriceDiscountSearch](#IsIntercompayPurchaseOrderCreationUsingPriceDiscountSearch)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsIntercompanyPurchaseOrderLinePriceChangeAllowed](#IsIntercompanyPurchaseOrderLinePriceChangeAllowed)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsIntercompanyPurchaseOrderLineDiscountChangeAllowed](#IsIntercompanyPurchaseOrderLineDiscountChangeAllowed)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsOriginalSalesOrderIntercompanyPurchaseOrderCustomerReferenceSynchronized](#IsOriginalSalesOrderIntercompanyPurchaseOrderCustomerReferenceSynchronized)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsOriginalSalesOrderIntercompanyPurchaseOrderRMANumberSynchronized](#IsOriginalSalesOrderIntercompanyPurchaseOrderRMANumberSynchronized)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsOriginalSalesOrderIntercompanyPurchaseOrderLinePriceDiscountSynchronized](#IsOriginalSalesOrderIntercompanyPurchaseOrderLinePriceDiscountSynchronized)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsIntercompanyPurchaseOrderIntercompanySalesOrderCustomerReferenceSynchronized](#IsIntercompanyPurchaseOrderIntercompanySalesOrderCustomerReferenceSynchronized)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsIntercompanyPurchaseOrderIntercompanySalesOrderRMANumberSynchronized](#IsIntercompanyPurchaseOrderIntercompanySalesOrderRMANumberSynchronized)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsIntercompanyPurchaseOrderIntercompanySalesOrderLineBatchNumberSynchronized](#IsIntercompanyPurchaseOrderIntercompanySalesOrderLineBatchNumberSynchronized)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsIntercompanyPurchaseOrderIntercompanySalesOrderLineSerialNumberSynchronized](#IsIntercompanyPurchaseOrderIntercompanySalesOrderLineSerialNumberSynchronized)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsIntercompanyPurchaseAgreementEffectiveOnHoldChangeAllowed](#IsIntercompanyPurchaseAgreementEffectiveOnHoldChangeAllowed)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsIntercompanyPurchaseAgreementValidityPeriodChangeAllowed](#IsIntercompanyPurchaseAgreementValidityPeriodChangeAllowed)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsIntercompanyPurchaseAgreementPriceChangeAllowed](#IsIntercompanyPurchaseAgreementPriceChangeAllowed)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[IsIntercompanyPurchaseAgreementDiscountChangeAllowed](#IsIntercompanyPurchaseAgreementDiscountChangeAllowed)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[Relationship_IntercompanyTradingPartnershipEntityRelationshipId](#Relationship_IntercompanyTradingPartnershipEntityRelationshipId)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|
|[BackingTable_InterCompanyTradingPartnerRelationshipId](#BackingTable_InterCompanyTradingPartnerRelationshipId)||<a href="IntercompanyTradingPartnershipProcurementPolicyEntity.md" target="_blank">ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity</a>|

### <a href=#VendorLegalEntityId name="VendorLegalEntityId">VendorLegalEntityId</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDirectDeliveryOriginalSalesOrderPackingSlipAutomaticallyPrinted name="IsDirectDeliveryOriginalSalesOrderPackingSlipAutomaticallyPrinted">IsDirectDeliveryOriginalSalesOrderPackingSlipAutomaticallyPrinted</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDirectDeliveryOriginalSalesOrderPackingSlipAutomaticallyPrinted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDirectDeliveryOriginalSalesOrderInvoiceAutomaticallyPosted name="IsDirectDeliveryOriginalSalesOrderInvoiceAutomaticallyPosted">IsDirectDeliveryOriginalSalesOrderInvoiceAutomaticallyPosted</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDirectDeliveryOriginalSalesOrderInvoiceAutomaticallyPosted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDirectDeliveryOriginalSalesOrderInvoiceAutomaticallyPrinted name="IsDirectDeliveryOriginalSalesOrderInvoiceAutomaticallyPrinted">IsDirectDeliveryOriginalSalesOrderInvoiceAutomaticallyPrinted</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDirectDeliveryOriginalSalesOrderInvoiceAutomaticallyPrinted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDirectDeliveryIntercompanyPurchaseOrderProductReceiptAutomaticallyPrinted name="IsDirectDeliveryIntercompanyPurchaseOrderProductReceiptAutomaticallyPrinted">IsDirectDeliveryIntercompanyPurchaseOrderProductReceiptAutomaticallyPrinted</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDirectDeliveryIntercompanyPurchaseOrderProductReceiptAutomaticallyPrinted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDirectDeliveryIntercompanyPurchaseOrderInvoiceAutomaticallyPosted name="IsDirectDeliveryIntercompanyPurchaseOrderInvoiceAutomaticallyPosted">IsDirectDeliveryIntercompanyPurchaseOrderInvoiceAutomaticallyPosted</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDirectDeliveryIntercompanyPurchaseOrderInvoiceAutomaticallyPosted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDirectDeliveryIntercompanyPurchaseOrderInvoiceAutomaticallyPrinted name="IsDirectDeliveryIntercompanyPurchaseOrderInvoiceAutomaticallyPrinted">IsDirectDeliveryIntercompanyPurchaseOrderInvoiceAutomaticallyPrinted</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDirectDeliveryIntercompanyPurchaseOrderInvoiceAutomaticallyPrinted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedChargeAllocationMethod name="FixedChargeAllocationMethod">FixedChargeAllocationMethod</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedChargeAllocationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOnlyStockedProductAllocatedFixedCharge name="IsOnlyStockedProductAllocatedFixedCharge">IsOnlyStockedProductAllocatedFixedCharge</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOnlyStockedProductAllocatedFixedCharge attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompayPurchaseOrderCreationUsingPriceDiscountSearch name="IsIntercompayPurchaseOrderCreationUsingPriceDiscountSearch">IsIntercompayPurchaseOrderCreationUsingPriceDiscountSearch</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompayPurchaseOrderCreationUsingPriceDiscountSearch attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanyPurchaseOrderLinePriceChangeAllowed name="IsIntercompanyPurchaseOrderLinePriceChangeAllowed">IsIntercompanyPurchaseOrderLinePriceChangeAllowed</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanyPurchaseOrderLinePriceChangeAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanyPurchaseOrderLineDiscountChangeAllowed name="IsIntercompanyPurchaseOrderLineDiscountChangeAllowed">IsIntercompanyPurchaseOrderLineDiscountChangeAllowed</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanyPurchaseOrderLineDiscountChangeAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOriginalSalesOrderIntercompanyPurchaseOrderCustomerReferenceSynchronized name="IsOriginalSalesOrderIntercompanyPurchaseOrderCustomerReferenceSynchronized">IsOriginalSalesOrderIntercompanyPurchaseOrderCustomerReferenceSynchronized</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOriginalSalesOrderIntercompanyPurchaseOrderCustomerReferenceSynchronized attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOriginalSalesOrderIntercompanyPurchaseOrderRMANumberSynchronized name="IsOriginalSalesOrderIntercompanyPurchaseOrderRMANumberSynchronized">IsOriginalSalesOrderIntercompanyPurchaseOrderRMANumberSynchronized</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOriginalSalesOrderIntercompanyPurchaseOrderRMANumberSynchronized attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOriginalSalesOrderIntercompanyPurchaseOrderLinePriceDiscountSynchronized name="IsOriginalSalesOrderIntercompanyPurchaseOrderLinePriceDiscountSynchronized">IsOriginalSalesOrderIntercompanyPurchaseOrderLinePriceDiscountSynchronized</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOriginalSalesOrderIntercompanyPurchaseOrderLinePriceDiscountSynchronized attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanyPurchaseOrderIntercompanySalesOrderCustomerReferenceSynchronized name="IsIntercompanyPurchaseOrderIntercompanySalesOrderCustomerReferenceSynchronized">IsIntercompanyPurchaseOrderIntercompanySalesOrderCustomerReferenceSynchronized</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanyPurchaseOrderIntercompanySalesOrderCustomerReferenceSynchronized attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanyPurchaseOrderIntercompanySalesOrderRMANumberSynchronized name="IsIntercompanyPurchaseOrderIntercompanySalesOrderRMANumberSynchronized">IsIntercompanyPurchaseOrderIntercompanySalesOrderRMANumberSynchronized</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanyPurchaseOrderIntercompanySalesOrderRMANumberSynchronized attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanyPurchaseOrderIntercompanySalesOrderLineBatchNumberSynchronized name="IsIntercompanyPurchaseOrderIntercompanySalesOrderLineBatchNumberSynchronized">IsIntercompanyPurchaseOrderIntercompanySalesOrderLineBatchNumberSynchronized</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanyPurchaseOrderIntercompanySalesOrderLineBatchNumberSynchronized attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanyPurchaseOrderIntercompanySalesOrderLineSerialNumberSynchronized name="IsIntercompanyPurchaseOrderIntercompanySalesOrderLineSerialNumberSynchronized">IsIntercompanyPurchaseOrderIntercompanySalesOrderLineSerialNumberSynchronized</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanyPurchaseOrderIntercompanySalesOrderLineSerialNumberSynchronized attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanyPurchaseAgreementEffectiveOnHoldChangeAllowed name="IsIntercompanyPurchaseAgreementEffectiveOnHoldChangeAllowed">IsIntercompanyPurchaseAgreementEffectiveOnHoldChangeAllowed</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanyPurchaseAgreementEffectiveOnHoldChangeAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanyPurchaseAgreementValidityPeriodChangeAllowed name="IsIntercompanyPurchaseAgreementValidityPeriodChangeAllowed">IsIntercompanyPurchaseAgreementValidityPeriodChangeAllowed</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanyPurchaseAgreementValidityPeriodChangeAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanyPurchaseAgreementPriceChangeAllowed name="IsIntercompanyPurchaseAgreementPriceChangeAllowed">IsIntercompanyPurchaseAgreementPriceChangeAllowed</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanyPurchaseAgreementPriceChangeAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanyPurchaseAgreementDiscountChangeAllowed name="IsIntercompanyPurchaseAgreementDiscountChangeAllowed">IsIntercompanyPurchaseAgreementDiscountChangeAllowed</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanyPurchaseAgreementDiscountChangeAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntercompanyTradingPartnershipEntityRelationshipId name="Relationship_IntercompanyTradingPartnershipEntityRelationshipId">Relationship_IntercompanyTradingPartnershipEntityRelationshipId</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntercompanyTradingPartnershipEntityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InterCompanyTradingPartnerRelationshipId name="BackingTable_InterCompanyTradingPartnerRelationshipId">BackingTable_InterCompanyTradingPartnerRelationshipId</a>

First included in: ProcurementAndSourcing/IntercompanyTradingPartnershipProcurementPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InterCompanyTradingPartnerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Group/InterCompanyTradingPartner.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/InterCompanyTradingPartner.cdm.json/InterCompanyTradingPartner</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Group/InterCompanyTradingPartner.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
