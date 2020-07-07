---
title: PurchPublishedRequestForQuotationReplyLineSummaryEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Reply line summary of published requests for quotations in ProcurementAndSourcing

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reply line summary of published requests for quotations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RFQNumber](#RFQNumber)||<a href="PurchPublishedRequestForQuotationReplyLineSummaryEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity</a>|
|[RFQCaseNumber](#RFQCaseNumber)||<a href="PurchPublishedRequestForQuotationReplyLineSummaryEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity</a>|
|[RFQCaseRequestingWorkerName](#RFQCaseRequestingWorkerName)||<a href="PurchPublishedRequestForQuotationReplyLineSummaryEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity</a>|
|[IsBidAwarded](#IsBidAwarded)||<a href="PurchPublishedRequestForQuotationReplyLineSummaryEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity</a>|
|[HighestRFQStatus](#HighestRFQStatus)||<a href="PurchPublishedRequestForQuotationReplyLineSummaryEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity</a>|
|[LowestRFQStatus](#LowestRFQStatus)||<a href="PurchPublishedRequestForQuotationReplyLineSummaryEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity</a>|
|[LineAmount](#LineAmount)||<a href="PurchPublishedRequestForQuotationReplyLineSummaryEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="PurchPublishedRequestForQuotationReplyLineSummaryEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity</a>|
|[VendorName](#VendorName)||<a href="PurchPublishedRequestForQuotationReplyLineSummaryEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity</a>|
|[TotalVendorScore](#TotalVendorScore)||<a href="PurchPublishedRequestForQuotationReplyLineSummaryEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity</a>|
|[TotalVendorScoreComment](#TotalVendorScoreComment)||<a href="PurchPublishedRequestForQuotationReplyLineSummaryEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity</a>|
|[VendorReplyStatus](#VendorReplyStatus)||<a href="PurchPublishedRequestForQuotationReplyLineSummaryEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity</a>|
|[RFQRecId](#RFQRecId)||<a href="PurchPublishedRequestForQuotationReplyLineSummaryEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchPublishedRequestForQuotationReplyLineSummaryEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity</a>|

### <a href=#RFQNumber name="RFQNumber">RFQNumber</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity (this entity)  

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

### <a href=#RFQCaseNumber name="RFQCaseNumber">RFQCaseNumber</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity (this entity)  

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

### <a href=#RFQCaseRequestingWorkerName name="RFQCaseRequestingWorkerName">RFQCaseRequestingWorkerName</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity (this entity)  

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

### <a href=#IsBidAwarded name="IsBidAwarded">IsBidAwarded</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Awarded</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBidAwarded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Awarded</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HighestRFQStatus name="HighestRFQStatus">HighestRFQStatus</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity (this entity)  

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

### <a href=#LineAmount name="LineAmount">LineAmount</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity (this entity)  

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

### <a href=#TotalVendorScore name="TotalVendorScore">TotalVendorScore</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalVendorScore attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalVendorScoreComment name="TotalVendorScoreComment">TotalVendorScoreComment</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalVendorScoreComment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorReplyStatus name="VendorReplyStatus">VendorReplyStatus</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Partial or complete reply</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorReplyStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Partial or complete reply</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQRecId name="RFQRecId">RFQRecId</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationReplyLineSummaryEntity (this entity)  

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
