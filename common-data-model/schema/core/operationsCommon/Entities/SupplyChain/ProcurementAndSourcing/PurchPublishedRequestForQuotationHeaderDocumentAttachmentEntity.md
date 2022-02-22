---
title: PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Published requests for quotations header attachments in ProcurementAndSourcing(PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Published requests for quotations header attachments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DocumentId](#DocumentId)||<a href="PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity</a>|
|[DocumentAttachmentTypeCode](#DocumentAttachmentTypeCode)||<a href="PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity</a>|
|[AttachmentDescription](#AttachmentDescription)||<a href="PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity</a>|
|[Notes](#Notes)||<a href="PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity</a>|
|[AccessRestriction](#AccessRestriction)||<a href="PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity</a>|
|[Attachment](#Attachment)||<a href="PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity</a>|
|[FileName](#FileName)||<a href="PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity</a>|
|[FileType](#FileType)||<a href="PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity</a>|
|[ActualCompanyId](#ActualCompanyId)||<a href="PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity</a>|
|[IsDefaultAttachment](#IsDefaultAttachment)||<a href="PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity</a>|
|[PublishedRFQCaseNumber](#PublishedRFQCaseNumber)||<a href="PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity</a>|
|[BackingTable_DocuRefEntityRelationshipId](#BackingTable_DocuRefEntityRelationshipId)||<a href="PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity.md" target="_blank">ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity</a>|

### <a href=#DocumentId name="DocumentId">DocumentId</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentAttachmentTypeCode name="DocumentAttachmentTypeCode">DocumentAttachmentTypeCode</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentAttachmentTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttachmentDescription name="AttachmentDescription">AttachmentDescription</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttachmentDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Notes name="Notes">Notes</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Notes attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccessRestriction name="AccessRestriction">AccessRestriction</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccessRestriction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Attachment name="Attachment">Attachment</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Attachment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FileName name="FileName">FileName</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FileType name="FileType">FileType</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualCompanyId name="ActualCompanyId">ActualCompanyId</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualCompanyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefaultAttachment name="IsDefaultAttachment">IsDefaultAttachment</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefaultAttachment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PublishedRFQCaseNumber name="PublishedRFQCaseNumber">PublishedRFQCaseNumber</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PublishedRFQCaseNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_DocuRefEntityRelationshipId name="BackingTable_DocuRefEntityRelationshipId">BackingTable_DocuRefEntityRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_DocuRefEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPublishedRequestForQuotationHeaderDocumentAttachmentEntity (this entity)  

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
