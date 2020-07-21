---
title: SalesDocumentProcessingPolicyEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Sales type document processing policies in SalesAndMarketing(SalesDocumentProcessingPolicyEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesDocumentProcessingPolicyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales type document processing policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BillOfLadingGenerationRule](#BillOfLadingGenerationRule)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[CreditNoteDateControlRule](#CreditNoteDateControlRule)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[CreditNoteDocumentDateControlRule](#CreditNoteDocumentDateControlRule)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[DefaultSummaryUpdateMethod](#DefaultSummaryUpdateMethod)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[InvoiceDateControlRule](#InvoiceDateControlRule)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[InvoiceDocumentDateControlRule](#InvoiceDocumentDateControlRule)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[IsConfirmationDeliveryAddressSpecific](#IsConfirmationDeliveryAddressSpecific)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[IsInvoiceDeliveryAddressSpecific](#IsInvoiceDeliveryAddressSpecific)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[WillInvoiceProcessDeleteInvoicedSalesOrder](#WillInvoiceProcessDeleteInvoicedSalesOrder)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[WillInvoiceProcessDeleteInvoicedSalesOrderLine](#WillInvoiceProcessDeleteInvoicedSalesOrderLine)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[WillInvoiceProcessingAutomaticallyReduceQuantity](#WillInvoiceProcessingAutomaticallyReduceQuantity)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[IsInvoiceSiteSpecific](#IsInvoiceSiteSpecific)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[WillSalesProcessesAcceptOverdelivery](#WillSalesProcessesAcceptOverdelivery)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[IsPackingSlipBeingAccounted](#IsPackingSlipBeingAccounted)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[IsPackingSlipDeliveryAddressSpecific](#IsPackingSlipDeliveryAddressSpecific)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[WillPackingSlipProcessingAutomaticallyReduceQuantity](#WillPackingSlipProcessingAutomaticallyReduceQuantity)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[IsPickingListDeliveryAddressSpecific](#IsPickingListDeliveryAddressSpecific)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[WillPickingListProcessingAutomaticallyReduceQuantity](#WillPickingListProcessingAutomaticallyReduceQuantity)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[IsQuantitySelectionBeingPrompted](#IsQuantitySelectionBeingPrompted)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[IsSalesDocumentProcessingUsingSettledCustomerTransactionExchangeRate](#IsSalesDocumentProcessingUsingSettledCustomerTransactionExchangeRate)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[WillSalesProcessesAcceptUnderdelivery](#WillSalesProcessesAcceptUnderdelivery)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[MaximumParallelDocumentProcessingBatchTaskSize](#MaximumParallelDocumentProcessingBatchTaskSize)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[OrderSummaryUpdateTypeDiscrepancyRule](#OrderSummaryUpdateTypeDiscrepancyRule)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[PickingListProcessingPickingRouteStatusUpdateRule](#PickingListProcessingPickingRouteStatusUpdateRule)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[ShippingSpecificationEntryRule](#ShippingSpecificationEntryRule)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[ExchangeRateDateRule](#ExchangeRateDateRule)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[IndependentDeliveryNoteNumbering](#IndependentDeliveryNoteNumbering)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[IsPickingListWarehouseSpecific](#IsPickingListWarehouseSpecific)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[BackingTable_SalesParametersRelationshipId](#BackingTable_SalesParametersRelationshipId)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesDocumentProcessingPolicyEntity.md" target="_blank">SalesAndMarketing/SalesDocumentProcessingPolicyEntity</a>|

### <a href=#BillOfLadingGenerationRule name="BillOfLadingGenerationRule">BillOfLadingGenerationRule</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillOfLadingGenerationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditNoteDateControlRule name="CreditNoteDateControlRule">CreditNoteDateControlRule</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditNoteDateControlRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditNoteDocumentDateControlRule name="CreditNoteDocumentDateControlRule">CreditNoteDocumentDateControlRule</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditNoteDocumentDateControlRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSummaryUpdateMethod name="DefaultSummaryUpdateMethod">DefaultSummaryUpdateMethod</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSummaryUpdateMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDateControlRule name="InvoiceDateControlRule">InvoiceDateControlRule</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDateControlRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDocumentDateControlRule name="InvoiceDocumentDateControlRule">InvoiceDocumentDateControlRule</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDocumentDateControlRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsConfirmationDeliveryAddressSpecific name="IsConfirmationDeliveryAddressSpecific">IsConfirmationDeliveryAddressSpecific</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsConfirmationDeliveryAddressSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInvoiceDeliveryAddressSpecific name="IsInvoiceDeliveryAddressSpecific">IsInvoiceDeliveryAddressSpecific</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInvoiceDeliveryAddressSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillInvoiceProcessDeleteInvoicedSalesOrder name="WillInvoiceProcessDeleteInvoicedSalesOrder">WillInvoiceProcessDeleteInvoicedSalesOrder</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillInvoiceProcessDeleteInvoicedSalesOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillInvoiceProcessDeleteInvoicedSalesOrderLine name="WillInvoiceProcessDeleteInvoicedSalesOrderLine">WillInvoiceProcessDeleteInvoicedSalesOrderLine</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillInvoiceProcessDeleteInvoicedSalesOrderLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillInvoiceProcessingAutomaticallyReduceQuantity name="WillInvoiceProcessingAutomaticallyReduceQuantity">WillInvoiceProcessingAutomaticallyReduceQuantity</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillInvoiceProcessingAutomaticallyReduceQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInvoiceSiteSpecific name="IsInvoiceSiteSpecific">IsInvoiceSiteSpecific</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInvoiceSiteSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSalesProcessesAcceptOverdelivery name="WillSalesProcessesAcceptOverdelivery">WillSalesProcessesAcceptOverdelivery</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesProcessesAcceptOverdelivery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPackingSlipBeingAccounted name="IsPackingSlipBeingAccounted">IsPackingSlipBeingAccounted</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPackingSlipBeingAccounted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPackingSlipDeliveryAddressSpecific name="IsPackingSlipDeliveryAddressSpecific">IsPackingSlipDeliveryAddressSpecific</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPackingSlipDeliveryAddressSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPackingSlipProcessingAutomaticallyReduceQuantity name="WillPackingSlipProcessingAutomaticallyReduceQuantity">WillPackingSlipProcessingAutomaticallyReduceQuantity</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPackingSlipProcessingAutomaticallyReduceQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPickingListDeliveryAddressSpecific name="IsPickingListDeliveryAddressSpecific">IsPickingListDeliveryAddressSpecific</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPickingListDeliveryAddressSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPickingListProcessingAutomaticallyReduceQuantity name="WillPickingListProcessingAutomaticallyReduceQuantity">WillPickingListProcessingAutomaticallyReduceQuantity</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPickingListProcessingAutomaticallyReduceQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuantitySelectionBeingPrompted name="IsQuantitySelectionBeingPrompted">IsQuantitySelectionBeingPrompted</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuantitySelectionBeingPrompted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesDocumentProcessingUsingSettledCustomerTransactionExchangeRate name="IsSalesDocumentProcessingUsingSettledCustomerTransactionExchangeRate">IsSalesDocumentProcessingUsingSettledCustomerTransactionExchangeRate</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesDocumentProcessingUsingSettledCustomerTransactionExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSalesProcessesAcceptUnderdelivery name="WillSalesProcessesAcceptUnderdelivery">WillSalesProcessesAcceptUnderdelivery</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesProcessesAcceptUnderdelivery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumParallelDocumentProcessingBatchTaskSize name="MaximumParallelDocumentProcessingBatchTaskSize">MaximumParallelDocumentProcessingBatchTaskSize</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumParallelDocumentProcessingBatchTaskSize attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderSummaryUpdateTypeDiscrepancyRule name="OrderSummaryUpdateTypeDiscrepancyRule">OrderSummaryUpdateTypeDiscrepancyRule</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderSummaryUpdateTypeDiscrepancyRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PickingListProcessingPickingRouteStatusUpdateRule name="PickingListProcessingPickingRouteStatusUpdateRule">PickingListProcessingPickingRouteStatusUpdateRule</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PickingListProcessingPickingRouteStatusUpdateRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingSpecificationEntryRule name="ShippingSpecificationEntryRule">ShippingSpecificationEntryRule</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingSpecificationEntryRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateDateRule name="ExchangeRateDateRule">ExchangeRateDateRule</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateDateRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IndependentDeliveryNoteNumbering name="IndependentDeliveryNoteNumbering">IndependentDeliveryNoteNumbering</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Independent delivery note numbering</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IndependentDeliveryNoteNumbering attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Independent delivery note numbering</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPickingListWarehouseSpecific name="IsPickingListWarehouseSpecific">IsPickingListWarehouseSpecific</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPickingListWarehouseSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_SalesParametersRelationshipId name="BackingTable_SalesParametersRelationshipId">BackingTable_SalesParametersRelationshipId</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SalesParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/SalesParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Parameter/SalesParameters.cdm.json/SalesParameters</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/SalesParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/SalesDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
