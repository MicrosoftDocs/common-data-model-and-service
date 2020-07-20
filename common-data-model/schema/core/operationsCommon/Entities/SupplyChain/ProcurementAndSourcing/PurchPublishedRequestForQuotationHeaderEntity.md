---
title: PurchPublishedRequestForQuotationHeaderEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Published requests for quotations in ProcurementAndSourcing(PurchPublishedRequestForQuotationHeaderEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Published requests for quotations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RFQCaseNumber](#RFQCaseNumber)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|
|[RFQCaseRecId](#RFQCaseRecId)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|
|[RFQCaseTitle](#RFQCaseTitle)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|
|[RequesterName](#RequesterName)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|
|[RequesterRecId](#RequesterRecId)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|
|[RequestingDepartmentName](#RequestingDepartmentName)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|
|[RFQSolicitationTypeName](#RFQSolicitationTypeName)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|
|[RFQBidType](#RFQBidType)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|
|[AreOnlyInvitedVendorBidsAllowed](#AreOnlyInvitedVendorBidsAllowed)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|
|[AreAlternateProductsAllowed](#AreAlternateProductsAllowed)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|
|[RFQDeliveryDate](#RFQDeliveryDate)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|
|[DeliveryAddressName](#DeliveryAddressName)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|
|[RFQExpirationDateTime](#RFQExpirationDateTime)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|
|[RFQCancellationDateTime](#RFQCancellationDateTime)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|
|[RFQCancellationReasonDescription](#RFQCancellationReasonDescription)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|
|[Relationship_HcmWorkerRelationshipId](#Relationship_HcmWorkerRelationshipId)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|
|[BackingTable_PurchRFQPublishTable_PSNRelationshipId](#BackingTable_PurchRFQPublishTable_PSNRelationshipId)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchPublishedRequestForQuotationHeaderEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity</a>|

### <a href=#RFQCaseNumber name="RFQCaseNumber">RFQCaseNumber</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

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

### <a href=#RFQCaseRecId name="RFQCaseRecId">RFQCaseRecId</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQCaseRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQCaseTitle name="RFQCaseTitle">RFQCaseTitle</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQCaseTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequesterName name="RequesterName">RequesterName</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequesterName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequesterRecId name="RequesterRecId">RequesterRecId</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequesterRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestingDepartmentName name="RequestingDepartmentName">RequestingDepartmentName</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestingDepartmentName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQSolicitationTypeName name="RFQSolicitationTypeName">RFQSolicitationTypeName</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQSolicitationTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQBidType name="RFQBidType">RFQBidType</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQBidType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreOnlyInvitedVendorBidsAllowed name="AreOnlyInvitedVendorBidsAllowed">AreOnlyInvitedVendorBidsAllowed</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreOnlyInvitedVendorBidsAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreAlternateProductsAllowed name="AreAlternateProductsAllowed">AreAlternateProductsAllowed</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreAlternateProductsAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

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

### <a href=#RFQDeliveryDate name="RFQDeliveryDate">RFQDeliveryDate</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQDeliveryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressName name="DeliveryAddressName">DeliveryAddressName</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQExpirationDateTime name="RFQExpirationDateTime">RFQExpirationDateTime</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQExpirationDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQCancellationDateTime name="RFQCancellationDateTime">RFQCancellationDateTime</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQCancellationDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQCancellationReasonDescription name="RFQCancellationReasonDescription">RFQCancellationReasonDescription</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQCancellationReasonDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HcmWorkerRelationshipId name="Relationship_HcmWorkerRelationshipId">Relationship_HcmWorkerRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmWorkerRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PurchRFQPublishTable_PSNRelationshipId name="BackingTable_PurchRFQPublishTable_PSNRelationshipId">BackingTable_PurchRFQPublishTable_PSNRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchRFQPublishTable_PSNRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchRFQPublishTable_PSN.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchRFQPublishTable_PSN.cdm.json/PurchRFQPublishTable_PSN</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchRFQPublishTable_PSN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderEntity (this entity)  

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
