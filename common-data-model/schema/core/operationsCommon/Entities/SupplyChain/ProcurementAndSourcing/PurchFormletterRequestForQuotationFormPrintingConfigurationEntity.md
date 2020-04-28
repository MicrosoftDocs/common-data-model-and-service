---
title: PurchFormletterRequestForQuotationFormPrintingConfigurationEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Request for quotation form printing configurations

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Request for quotation form printing configurations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsInventoryStatusIdDisplayed](#IsInventoryStatusIdDisplayed)||<a href="PurchFormletterRequestForQuotationFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity</a>|
|[IsItemBatchNumberDisplayed](#IsItemBatchNumberDisplayed)||<a href="PurchFormletterRequestForQuotationFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity</a>|
|[IsItemSerialNumberDisplayed](#IsItemSerialNumberDisplayed)||<a href="PurchFormletterRequestForQuotationFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity</a>|
|[IsLicensePlateNumberDisplayed](#IsLicensePlateNumberDisplayed)||<a href="PurchFormletterRequestForQuotationFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity</a>|
|[IsProductColorIdDisplayed](#IsProductColorIdDisplayed)||<a href="PurchFormletterRequestForQuotationFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity</a>|
|[IsProductConfigurationIdDisplayed](#IsProductConfigurationIdDisplayed)||<a href="PurchFormletterRequestForQuotationFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity</a>|
|[IsProductSizeIdDisplayed](#IsProductSizeIdDisplayed)||<a href="PurchFormletterRequestForQuotationFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity</a>|
|[IsProductStyleIdDisplayed](#IsProductStyleIdDisplayed)||<a href="PurchFormletterRequestForQuotationFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity</a>|
|[IsProductVersionIdDisplayed](#IsProductVersionIdDisplayed)||<a href="PurchFormletterRequestForQuotationFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity</a>|
|[IsReceivingSiteIdDisplayed](#IsReceivingSiteIdDisplayed)||<a href="PurchFormletterRequestForQuotationFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity</a>|
|[IsReceivingWarehouseIdDisplayed](#IsReceivingWarehouseIdDisplayed)||<a href="PurchFormletterRequestForQuotationFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity</a>|
|[InventDimRFQ](#InventDimRFQ)||<a href="PurchFormletterRequestForQuotationFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity</a>|
|[PaperFormat](#PaperFormat)||<a href="PurchFormletterRequestForQuotationFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity</a>|
|[DocumentAttachmentDisplayRule](#DocumentAttachmentDisplayRule)||<a href="PurchFormletterRequestForQuotationFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity</a>|
|[DisplayedDocumentAttachmentTypeCode](#DisplayedDocumentAttachmentTypeCode)||<a href="PurchFormletterRequestForQuotationFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity</a>|
|[BackingTable_VendFormletterParametersRelationshipId](#BackingTable_VendFormletterParametersRelationshipId)||<a href="PurchFormletterRequestForQuotationFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchFormletterRequestForQuotationFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity</a>|

### <a href=#IsInventoryStatusIdDisplayed name="IsInventoryStatusIdDisplayed">IsInventoryStatusIdDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryStatusIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsItemBatchNumberDisplayed name="IsItemBatchNumberDisplayed">IsItemBatchNumberDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsItemBatchNumberDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsItemSerialNumberDisplayed name="IsItemSerialNumberDisplayed">IsItemSerialNumberDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsItemSerialNumberDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLicensePlateNumberDisplayed name="IsLicensePlateNumberDisplayed">IsLicensePlateNumberDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLicensePlateNumberDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductColorIdDisplayed name="IsProductColorIdDisplayed">IsProductColorIdDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductColorIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductConfigurationIdDisplayed name="IsProductConfigurationIdDisplayed">IsProductConfigurationIdDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductConfigurationIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductSizeIdDisplayed name="IsProductSizeIdDisplayed">IsProductSizeIdDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductSizeIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductStyleIdDisplayed name="IsProductStyleIdDisplayed">IsProductStyleIdDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductStyleIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductVersionIdDisplayed name="IsProductVersionIdDisplayed">IsProductVersionIdDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductVersionIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReceivingSiteIdDisplayed name="IsReceivingSiteIdDisplayed">IsReceivingSiteIdDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReceivingSiteIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReceivingWarehouseIdDisplayed name="IsReceivingWarehouseIdDisplayed">IsReceivingWarehouseIdDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReceivingWarehouseIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventDimRFQ name="InventDimRFQ">InventDimRFQ</a>

First included in: ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimRFQ attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaperFormat name="PaperFormat">PaperFormat</a>

First included in: ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaperFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentAttachmentDisplayRule name="DocumentAttachmentDisplayRule">DocumentAttachmentDisplayRule</a>

First included in: ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentAttachmentDisplayRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayedDocumentAttachmentTypeCode name="DisplayedDocumentAttachmentTypeCode">DisplayedDocumentAttachmentTypeCode</a>

First included in: ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayedDocumentAttachmentTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_VendFormletterParametersRelationshipId name="BackingTable_VendFormletterParametersRelationshipId">BackingTable_VendFormletterParametersRelationshipId</a>

First included in: ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_VendFormletterParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsPayable/Parameter/VendFormletterParameters.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Parameter/VendFormletterParameters.cdm.json/VendFormletterParameters</a></td><td><a href="../../../Tables/Finance/AccountsPayable/Parameter/VendFormletterParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchFormletterRequestForQuotationFormPrintingConfigurationEntity (this entity)  

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
