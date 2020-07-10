---
title: IntercompanyTradingPartnershipSalesPolicyEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Intercompany sales policies in SalesAndMarketing(IntercompanyTradingPartnershipSalesPolicyEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Intercompany sales policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CustomerLegalEntityId](#CustomerLegalEntityId)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IntercompanySalesOrderNumberingMethod](#IntercompanySalesOrderNumberingMethod)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IntercompanySalesOrderNumberSequenceCode](#IntercompanySalesOrderNumberSequenceCode)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IsIntercompanySalesOrderOriginalCustomerSummaryUpdateAllowed](#IsIntercompanySalesOrderOriginalCustomerSummaryUpdateAllowed)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IsIntercompanySalesOrderPickinglistAutomaticallyPrinted](#IsIntercompanySalesOrderPickinglistAutomaticallyPrinted)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IntercompanyVendorPaymentJournalNameId](#IntercompanyVendorPaymentJournalNameId)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IsIntercompanyVendorPaymentJournalAutomaticallyPosted](#IsIntercompanyVendorPaymentJournalAutomaticallyPosted)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IsIntercompanySalesOrderLineUnitPriceEqualCostPriceWhenInvoicePosting](#IsIntercompanySalesOrderLineUnitPriceEqualCostPriceWhenInvoicePosting)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IsOriginalSalesOrderInvoicePostingAllowedWithUnpostedIntercompanySalesOrder](#IsOriginalSalesOrderInvoicePostingAllowedWithUnpostedIntercompanySalesOrder)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IsIntercompaySalesOrderCreationUsingPriceDiscountSearch](#IsIntercompaySalesOrderCreationUsingPriceDiscountSearch)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IsIntercompanySalesOrderLinePriceChangeAllowed](#IsIntercompanySalesOrderLinePriceChangeAllowed)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IsIntercompanySalesOrderLineDiscountChangeAllowed](#IsIntercompanySalesOrderLineDiscountChangeAllowed)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IsIntercompanyPurchaseOrderIntercompanySalesOrderCustomerReferenceSynchronized](#IsIntercompanyPurchaseOrderIntercompanySalesOrderCustomerReferenceSynchronized)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IsIntercompanyPurchaseOrderIntercompanySalesOrderRMANumberSynchronized](#IsIntercompanyPurchaseOrderIntercompanySalesOrderRMANumberSynchronized)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IsIntercompanyPurchaseOrderIntercompanySalesOrderLineBatchNumberSynchronized](#IsIntercompanyPurchaseOrderIntercompanySalesOrderLineBatchNumberSynchronized)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IsIntercompanyPurchaseOrderIntercompanySalesOrderLineSerialNumberSynchronized](#IsIntercompanyPurchaseOrderIntercompanySalesOrderLineSerialNumberSynchronized)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IsIntercompanySalesAgreementEffectiveOnHoldChangeAllowed](#IsIntercompanySalesAgreementEffectiveOnHoldChangeAllowed)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IsIntercompanySalesAgreementValidityPeriodChangeAllowed](#IsIntercompanySalesAgreementValidityPeriodChangeAllowed)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IsIntercompanySalesAgreementPriceChangeAllowed](#IsIntercompanySalesAgreementPriceChangeAllowed)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[IsIntercompanySalesAgreementDiscountChangeAllowed](#IsIntercompanySalesAgreementDiscountChangeAllowed)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[Relationship_IntercompanyTradingPartnershipEntityRelationshipId](#Relationship_IntercompanyTradingPartnershipEntityRelationshipId)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|
|[BackingTable_InterCompanyTradingPartnerRelationshipId](#BackingTable_InterCompanyTradingPartnerRelationshipId)||<a href="IntercompanyTradingPartnershipSalesPolicyEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity</a>|

### <a href=#CustomerLegalEntityId name="CustomerLegalEntityId">CustomerLegalEntityId</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntercompanySalesOrderNumberingMethod name="IntercompanySalesOrderNumberingMethod">IntercompanySalesOrderNumberingMethod</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntercompanySalesOrderNumberingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntercompanySalesOrderNumberSequenceCode name="IntercompanySalesOrderNumberSequenceCode">IntercompanySalesOrderNumberSequenceCode</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntercompanySalesOrderNumberSequenceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanySalesOrderOriginalCustomerSummaryUpdateAllowed name="IsIntercompanySalesOrderOriginalCustomerSummaryUpdateAllowed">IsIntercompanySalesOrderOriginalCustomerSummaryUpdateAllowed</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanySalesOrderOriginalCustomerSummaryUpdateAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanySalesOrderPickinglistAutomaticallyPrinted name="IsIntercompanySalesOrderPickinglistAutomaticallyPrinted">IsIntercompanySalesOrderPickinglistAutomaticallyPrinted</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanySalesOrderPickinglistAutomaticallyPrinted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntercompanyVendorPaymentJournalNameId name="IntercompanyVendorPaymentJournalNameId">IntercompanyVendorPaymentJournalNameId</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntercompanyVendorPaymentJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanyVendorPaymentJournalAutomaticallyPosted name="IsIntercompanyVendorPaymentJournalAutomaticallyPosted">IsIntercompanyVendorPaymentJournalAutomaticallyPosted</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanyVendorPaymentJournalAutomaticallyPosted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanySalesOrderLineUnitPriceEqualCostPriceWhenInvoicePosting name="IsIntercompanySalesOrderLineUnitPriceEqualCostPriceWhenInvoicePosting">IsIntercompanySalesOrderLineUnitPriceEqualCostPriceWhenInvoicePosting</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanySalesOrderLineUnitPriceEqualCostPriceWhenInvoicePosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOriginalSalesOrderInvoicePostingAllowedWithUnpostedIntercompanySalesOrder name="IsOriginalSalesOrderInvoicePostingAllowedWithUnpostedIntercompanySalesOrder">IsOriginalSalesOrderInvoicePostingAllowedWithUnpostedIntercompanySalesOrder</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOriginalSalesOrderInvoicePostingAllowedWithUnpostedIntercompanySalesOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompaySalesOrderCreationUsingPriceDiscountSearch name="IsIntercompaySalesOrderCreationUsingPriceDiscountSearch">IsIntercompaySalesOrderCreationUsingPriceDiscountSearch</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompaySalesOrderCreationUsingPriceDiscountSearch attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanySalesOrderLinePriceChangeAllowed name="IsIntercompanySalesOrderLinePriceChangeAllowed">IsIntercompanySalesOrderLinePriceChangeAllowed</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanySalesOrderLinePriceChangeAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanySalesOrderLineDiscountChangeAllowed name="IsIntercompanySalesOrderLineDiscountChangeAllowed">IsIntercompanySalesOrderLineDiscountChangeAllowed</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanySalesOrderLineDiscountChangeAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanyPurchaseOrderIntercompanySalesOrderCustomerReferenceSynchronized name="IsIntercompanyPurchaseOrderIntercompanySalesOrderCustomerReferenceSynchronized">IsIntercompanyPurchaseOrderIntercompanySalesOrderCustomerReferenceSynchronized</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

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

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

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

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

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

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

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

### <a href=#IsIntercompanySalesAgreementEffectiveOnHoldChangeAllowed name="IsIntercompanySalesAgreementEffectiveOnHoldChangeAllowed">IsIntercompanySalesAgreementEffectiveOnHoldChangeAllowed</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanySalesAgreementEffectiveOnHoldChangeAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanySalesAgreementValidityPeriodChangeAllowed name="IsIntercompanySalesAgreementValidityPeriodChangeAllowed">IsIntercompanySalesAgreementValidityPeriodChangeAllowed</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanySalesAgreementValidityPeriodChangeAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanySalesAgreementPriceChangeAllowed name="IsIntercompanySalesAgreementPriceChangeAllowed">IsIntercompanySalesAgreementPriceChangeAllowed</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanySalesAgreementPriceChangeAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIntercompanySalesAgreementDiscountChangeAllowed name="IsIntercompanySalesAgreementDiscountChangeAllowed">IsIntercompanySalesAgreementDiscountChangeAllowed</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIntercompanySalesAgreementDiscountChangeAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntercompanyTradingPartnershipEntityRelationshipId name="Relationship_IntercompanyTradingPartnershipEntityRelationshipId">Relationship_IntercompanyTradingPartnershipEntityRelationshipId</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

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

First included in: SalesAndMarketing/IntercompanyTradingPartnershipSalesPolicyEntity (this entity)  

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
