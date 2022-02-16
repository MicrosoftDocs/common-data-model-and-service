---
title: EcoResDocumentAttachmentEntity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Document attachments related to products in ProductInformationManagement(EcoResDocumentAttachmentEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResDocumentAttachmentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Document attachments related to products</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ParentLegalEntityId](#ParentLegalEntityId)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[ParentTableId](#ParentTableId)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[ParentRecordId](#ParentRecordId)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[AttachmentDescription](#AttachmentDescription)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[DocumentAttachmentTypeCode](#DocumentAttachmentTypeCode)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[DocumentAttachmentTypeLegalEntityId](#DocumentAttachmentTypeLegalEntityId)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[AttachmentType](#AttachmentType)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[Attachment](#Attachment)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[Notes](#Notes)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[AccessRestriction](#AccessRestriction)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[AttachingUserId](#AttachingUserId)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[AttachedDateTime](#AttachedDateTime)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[FileType](#FileType)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[OriginalFileName](#OriginalFileName)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[FileLocation](#FileLocation)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[DocumentStorageProviderType](#DocumentStorageProviderType)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[IsProductImage](#IsProductImage)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[IsDefaultProductImage](#IsDefaultProductImage)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[ProductImageUsage](#ProductImageUsage)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|
|[BackingTable_DocuRefRelationshipId](#BackingTable_DocuRefRelationshipId)||<a href="EcoResDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/EcoResDocumentAttachmentEntity</a>|

### <a href=#ParentLegalEntityId name="ParentLegalEntityId">ParentLegalEntityId</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentTableId name="ParentTableId">ParentTableId</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentRecordId name="ParentRecordId">ParentRecordId</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttachmentDescription name="AttachmentDescription">AttachmentDescription</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttachmentDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentAttachmentTypeCode name="DocumentAttachmentTypeCode">DocumentAttachmentTypeCode</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

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

### <a href=#DocumentAttachmentTypeLegalEntityId name="DocumentAttachmentTypeLegalEntityId">DocumentAttachmentTypeLegalEntityId</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentAttachmentTypeLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttachmentType name="AttachmentType">AttachmentType</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttachmentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Attachment name="Attachment">Attachment</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

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

### <a href=#Notes name="Notes">Notes</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

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

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

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

### <a href=#AttachingUserId name="AttachingUserId">AttachingUserId</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttachingUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttachedDateTime name="AttachedDateTime">AttachedDateTime</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttachedDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FileType name="FileType">FileType</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

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

### <a href=#OriginalFileName name="OriginalFileName">OriginalFileName</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalFileName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FileLocation name="FileLocation">FileLocation</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentStorageProviderType name="DocumentStorageProviderType">DocumentStorageProviderType</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentStorageProviderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductImage name="IsProductImage">IsProductImage</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductImage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefaultProductImage name="IsDefaultProductImage">IsDefaultProductImage</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefaultProductImage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductImageUsage name="ProductImageUsage">ProductImageUsage</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductImageUsage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_DocuRefRelationshipId name="BackingTable_DocuRefRelationshipId">BackingTable_DocuRefRelationshipId</a>

First included in: ProductInformationManagement/EcoResDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_DocuRefRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/System/SystemAdministration/WorksheetLine/DocuRef.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/WorksheetLine/DocuRef.cdm.json/DocuRef</a></td><td><a href="../../../Tables/System/SystemAdministration/WorksheetLine/DocuRef.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
