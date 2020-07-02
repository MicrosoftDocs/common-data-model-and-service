---
title: PurchPublishedRequestForQuotationAndReplyLineEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Published requests for quotations and reply lines detail

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Published requests for quotations and reply lines detail</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RFQNumber](#RFQNumber)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[ReplyLineNumber](#ReplyLineNumber)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[IsAlternateProduct](#IsAlternateProduct)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[LineType](#LineType)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[LineDescription](#LineDescription)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[ReplyFixedPriceCharges](#ReplyFixedPriceCharges)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[ReplyPurchaseQuantity](#ReplyPurchaseQuantity)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[ReplyPurchaseUnitSymbol](#ReplyPurchaseUnitSymbol)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[ReplyPurchasePrice](#ReplyPurchasePrice)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[ReplyLineAmount](#ReplyLineAmount)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[ReplyLineDiscountAmount](#ReplyLineDiscountAmount)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[ReplyLineDiscountPercentage](#ReplyLineDiscountPercentage)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[ReplyMultilineDiscountAmount](#ReplyMultilineDiscountAmount)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[ReplyMultilineDiscountPercentage](#ReplyMultilineDiscountPercentage)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[ReplyComment](#ReplyComment)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[ReplyLineValidFromDate](#ReplyLineValidFromDate)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[ReplyLineValidToDate](#ReplyLineValidToDate)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[ReplyLineLeadTime](#ReplyLineLeadTime)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[ReplyLineWorkingDays](#ReplyLineWorkingDays)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[RFQCaseNumber](#RFQCaseNumber)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[RFQStatus](#RFQStatus)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[RFQCaseRequestingWorkerName](#RFQCaseRequestingWorkerName)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[ProjectCategoryId](#ProjectCategoryId)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[PurchaseOrderNumber](#PurchaseOrderNumber)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[RequestedFixedPriceCharges](#RequestedFixedPriceCharges)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[RequestedPurchaseQuantity](#RequestedPurchaseQuantity)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[RequestedPurchaseUnitSymbol](#RequestedPurchaseUnitSymbol)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[RequestedPurchasePrice](#RequestedPurchasePrice)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[RequestedLineAmount](#RequestedLineAmount)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[RequestedLineDiscountAmount](#RequestedLineDiscountAmount)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[RequestedLineDiscountPercentage](#RequestedLineDiscountPercentage)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[RequestedMultilineDiscountAmount](#RequestedMultilineDiscountAmount)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[RequestedMultilineDiscountPercentage](#RequestedMultilineDiscountPercentage)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[HighestRFQStatus](#HighestRFQStatus)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[LowestRFQStatus](#LowestRFQStatus)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[VendorName](#VendorName)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchPublishedRequestForQuotationAndReplyLineEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity</a>|

### <a href=#RFQNumber name="RFQNumber">RFQNumber</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplyLineNumber name="ReplyLineNumber">ReplyLineNumber</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAlternateProduct name="IsAlternateProduct">IsAlternateProduct</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAlternateProduct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineType name="LineType">LineType</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDescription name="LineDescription">LineDescription</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplyFixedPriceCharges name="ReplyFixedPriceCharges">ReplyFixedPriceCharges</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyFixedPriceCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplyPurchaseQuantity name="ReplyPurchaseQuantity">ReplyPurchaseQuantity</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyPurchaseQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplyPurchaseUnitSymbol name="ReplyPurchaseUnitSymbol">ReplyPurchaseUnitSymbol</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyPurchaseUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplyPurchasePrice name="ReplyPurchasePrice">ReplyPurchasePrice</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyPurchasePrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplyLineAmount name="ReplyLineAmount">ReplyLineAmount</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplyLineDiscountAmount name="ReplyLineDiscountAmount">ReplyLineDiscountAmount</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplyLineDiscountPercentage name="ReplyLineDiscountPercentage">ReplyLineDiscountPercentage</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplyMultilineDiscountAmount name="ReplyMultilineDiscountAmount">ReplyMultilineDiscountAmount</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyMultilineDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplyMultilineDiscountPercentage name="ReplyMultilineDiscountPercentage">ReplyMultilineDiscountPercentage</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyMultilineDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplyComment name="ReplyComment">ReplyComment</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyComment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplyLineValidFromDate name="ReplyLineValidFromDate">ReplyLineValidFromDate</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineValidFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplyLineValidToDate name="ReplyLineValidToDate">ReplyLineValidToDate</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineValidToDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplyLineLeadTime name="ReplyLineLeadTime">ReplyLineLeadTime</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineLeadTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplyLineWorkingDays name="ReplyLineWorkingDays">ReplyLineWorkingDays</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplyLineWorkingDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQCaseNumber name="RFQCaseNumber">RFQCaseNumber</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQCaseNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQStatus name="RFQStatus">RFQStatus</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQCaseRequestingWorkerName name="RFQCaseRequestingWorkerName">RFQCaseRequestingWorkerName</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQCaseRequestingWorkerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectCategoryId name="ProjectCategoryId">ProjectCategoryId</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderNumber name="PurchaseOrderNumber">PurchaseOrderNumber</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedFixedPriceCharges name="RequestedFixedPriceCharges">RequestedFixedPriceCharges</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedFixedPriceCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedPurchaseQuantity name="RequestedPurchaseQuantity">RequestedPurchaseQuantity</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedPurchaseQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedPurchaseUnitSymbol name="RequestedPurchaseUnitSymbol">RequestedPurchaseUnitSymbol</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedPurchaseUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedPurchasePrice name="RequestedPurchasePrice">RequestedPurchasePrice</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedPurchasePrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedLineAmount name="RequestedLineAmount">RequestedLineAmount</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedLineAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedLineDiscountAmount name="RequestedLineDiscountAmount">RequestedLineDiscountAmount</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedLineDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedLineDiscountPercentage name="RequestedLineDiscountPercentage">RequestedLineDiscountPercentage</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedLineDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedMultilineDiscountAmount name="RequestedMultilineDiscountAmount">RequestedMultilineDiscountAmount</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedMultilineDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedMultilineDiscountPercentage name="RequestedMultilineDiscountPercentage">RequestedMultilineDiscountPercentage</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedMultilineDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HighestRFQStatus name="HighestRFQStatus">HighestRFQStatus</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HighestRFQStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LowestRFQStatus name="LowestRFQStatus">LowestRFQStatus</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowestRFQStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

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

### <a href=#VendorName name="VendorName">VendorName</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationAndReplyLineEntity (this entity)  

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
