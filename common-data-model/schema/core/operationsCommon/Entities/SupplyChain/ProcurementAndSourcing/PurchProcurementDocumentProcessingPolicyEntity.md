---
title: PurchProcurementDocumentProcessingPolicyEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Procurement type document processing policies in ProcurementAndSourcing(PurchProcurementDocumentProcessingPolicyEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Procurement type document processing policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AreThreeWayMatchedPurchaseOrderLinesDecentrallyReceivedOnly](#AreThreeWayMatchedPurchaseOrderLinesDecentrallyReceivedOnly)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[DefaultSummaryUpdateMethod](#DefaultSummaryUpdateMethod)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[DuplicateProductReceiptNumberValidationRule](#DuplicateProductReceiptNumberValidationRule)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[WillDocumentProcessingAutomaticallyCalculateTotalDiscount](#WillDocumentProcessingAutomaticallyCalculateTotalDiscount)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[IsInvoiceDeliveryAddressSpecific](#IsInvoiceDeliveryAddressSpecific)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[WillProcumentProcessesAcceptOverdelivery](#WillProcumentProcessesAcceptOverdelivery)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[WillProductReceiptProcessAccountCharges](#WillProductReceiptProcessAccountCharges)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[IsProductReceiptDeliveryAddressSpecific](#IsProductReceiptDeliveryAddressSpecific)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[IsQuantitySelectionBeingPrompted](#IsQuantitySelectionBeingPrompted)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[WillSalesOrderPrepaymentAutomaticallyCreateDropShipment](#WillSalesOrderPrepaymentAutomaticallyCreateDropShipment)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[WillProcumentProcessesAcceptUnderdelivery](#WillProcumentProcessesAcceptUnderdelivery)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[MaximumParallelDocumentProcessingBatchTaskSize](#MaximumParallelDocumentProcessingBatchTaskSize)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[OrderSummaryUpdateTypeDiscrepancyRule](#OrderSummaryUpdateTypeDiscrepancyRule)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[RFQAmendmentNotificationEmailTemplateId](#RFQAmendmentNotificationEmailTemplateId)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[ReceivedQuotationTradeAgreementJournalName](#ReceivedQuotationTradeAgreementJournalName)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[RFQCancellationNotificationEmailTemplateId](#RFQCancellationNotificationEmailTemplateId)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[ExchangeRateDateRule](#ExchangeRateDateRule)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[IndependentDeliveryNoteNumbering](#IndependentDeliveryNoteNumbering)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[BackingTable_PurchParametersRelationshipId](#BackingTable_PurchParametersRelationshipId)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchProcurementDocumentProcessingPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity</a>|

### <a href=#AreThreeWayMatchedPurchaseOrderLinesDecentrallyReceivedOnly name="AreThreeWayMatchedPurchaseOrderLinesDecentrallyReceivedOnly">AreThreeWayMatchedPurchaseOrderLinesDecentrallyReceivedOnly</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreThreeWayMatchedPurchaseOrderLinesDecentrallyReceivedOnly attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultSummaryUpdateMethod name="DefaultSummaryUpdateMethod">DefaultSummaryUpdateMethod</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

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

### <a href=#DuplicateProductReceiptNumberValidationRule name="DuplicateProductReceiptNumberValidationRule">DuplicateProductReceiptNumberValidationRule</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DuplicateProductReceiptNumberValidationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillDocumentProcessingAutomaticallyCalculateTotalDiscount name="WillDocumentProcessingAutomaticallyCalculateTotalDiscount">WillDocumentProcessingAutomaticallyCalculateTotalDiscount</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillDocumentProcessingAutomaticallyCalculateTotalDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInvoiceDeliveryAddressSpecific name="IsInvoiceDeliveryAddressSpecific">IsInvoiceDeliveryAddressSpecific</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

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

### <a href=#WillProcumentProcessesAcceptOverdelivery name="WillProcumentProcessesAcceptOverdelivery">WillProcumentProcessesAcceptOverdelivery</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProcumentProcessesAcceptOverdelivery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductReceiptProcessAccountCharges name="WillProductReceiptProcessAccountCharges">WillProductReceiptProcessAccountCharges</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductReceiptProcessAccountCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductReceiptDeliveryAddressSpecific name="IsProductReceiptDeliveryAddressSpecific">IsProductReceiptDeliveryAddressSpecific</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductReceiptDeliveryAddressSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuantitySelectionBeingPrompted name="IsQuantitySelectionBeingPrompted">IsQuantitySelectionBeingPrompted</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

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

### <a href=#WillSalesOrderPrepaymentAutomaticallyCreateDropShipment name="WillSalesOrderPrepaymentAutomaticallyCreateDropShipment">WillSalesOrderPrepaymentAutomaticallyCreateDropShipment</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSalesOrderPrepaymentAutomaticallyCreateDropShipment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProcumentProcessesAcceptUnderdelivery name="WillProcumentProcessesAcceptUnderdelivery">WillProcumentProcessesAcceptUnderdelivery</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProcumentProcessesAcceptUnderdelivery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumParallelDocumentProcessingBatchTaskSize name="MaximumParallelDocumentProcessingBatchTaskSize">MaximumParallelDocumentProcessingBatchTaskSize</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

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

### <a href=#RFQAmendmentNotificationEmailTemplateId name="RFQAmendmentNotificationEmailTemplateId">RFQAmendmentNotificationEmailTemplateId</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQAmendmentNotificationEmailTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivedQuotationTradeAgreementJournalName name="ReceivedQuotationTradeAgreementJournalName">ReceivedQuotationTradeAgreementJournalName</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivedQuotationTradeAgreementJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQCancellationNotificationEmailTemplateId name="RFQCancellationNotificationEmailTemplateId">RFQCancellationNotificationEmailTemplateId</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQCancellationNotificationEmailTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateDateRule name="ExchangeRateDateRule">ExchangeRateDateRule</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

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

### <a href=#BackingTable_PurchParametersRelationshipId name="BackingTable_PurchParametersRelationshipId">BackingTable_PurchParametersRelationshipId</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchParameters.cdm.json/PurchParameters</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentProcessingPolicyEntity (this entity)  

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
