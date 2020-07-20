---
title: PmfFormulaVersionDocumentAttachmentEntity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Formula version document attachments in ProductInformationManagement(PmfFormulaVersionDocumentAttachmentEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Formula version document attachments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DocumentId](#DocumentId)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[DocumentAttachmentTypeCode](#DocumentAttachmentTypeCode)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[AttachmentDescription](#AttachmentDescription)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[Notes](#Notes)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[AccessRestriction](#AccessRestriction)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[Attachment](#Attachment)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[FileName](#FileName)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[FileType](#FileType)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[ActualCompanyId](#ActualCompanyId)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[IsDefaultAttachment](#IsDefaultAttachment)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[FormulaVersionManufacturedItemNumber](#FormulaVersionManufacturedItemNumber)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[FormulaId](#FormulaId)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[FormulaVersionProductionSiteId](#FormulaVersionProductionSiteId)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[FormulaVersionProductConfigurationId](#FormulaVersionProductConfigurationId)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[FormulaVersionProductColorId](#FormulaVersionProductColorId)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[FormulaVersionProductSizeId](#FormulaVersionProductSizeId)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[FormulaVersionProductStyleId](#FormulaVersionProductStyleId)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[FormulaVersionProductVersionId](#FormulaVersionProductVersionId)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[IsFormulaVersionActive](#IsFormulaVersionActive)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[FormulaVersionValidFromDate](#FormulaVersionValidFromDate)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[FormulaVersionFromQuantity](#FormulaVersionFromQuantity)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[BackingTable_DocuRefEntityRelationshipId](#BackingTable_DocuRefEntityRelationshipId)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PmfFormulaVersionDocumentAttachmentEntity.md" target="_blank">ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity</a>|

### <a href=#DocumentId name="DocumentId">DocumentId</a>

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

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

### <a href=#FormulaVersionManufacturedItemNumber name="FormulaVersionManufacturedItemNumber">FormulaVersionManufacturedItemNumber</a>

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormulaVersionManufacturedItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormulaId name="FormulaId">FormulaId</a>

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormulaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormulaVersionProductionSiteId name="FormulaVersionProductionSiteId">FormulaVersionProductionSiteId</a>

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormulaVersionProductionSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormulaVersionProductConfigurationId name="FormulaVersionProductConfigurationId">FormulaVersionProductConfigurationId</a>

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormulaVersionProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormulaVersionProductColorId name="FormulaVersionProductColorId">FormulaVersionProductColorId</a>

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormulaVersionProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormulaVersionProductSizeId name="FormulaVersionProductSizeId">FormulaVersionProductSizeId</a>

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormulaVersionProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormulaVersionProductStyleId name="FormulaVersionProductStyleId">FormulaVersionProductStyleId</a>

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormulaVersionProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormulaVersionProductVersionId name="FormulaVersionProductVersionId">FormulaVersionProductVersionId</a>

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormulaVersionProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFormulaVersionActive name="IsFormulaVersionActive">IsFormulaVersionActive</a>

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFormulaVersionActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormulaVersionValidFromDate name="FormulaVersionValidFromDate">FormulaVersionValidFromDate</a>

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormulaVersionValidFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormulaVersionFromQuantity name="FormulaVersionFromQuantity">FormulaVersionFromQuantity</a>

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormulaVersionFromQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_DocuRefEntityRelationshipId name="BackingTable_DocuRefEntityRelationshipId">BackingTable_DocuRefEntityRelationshipId</a>

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

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

First included in: ProductInformationManagement/PmfFormulaVersionDocumentAttachmentEntity (this entity)  

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
