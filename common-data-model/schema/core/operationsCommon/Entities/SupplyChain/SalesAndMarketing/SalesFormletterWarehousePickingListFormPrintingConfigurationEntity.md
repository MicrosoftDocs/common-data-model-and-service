---
title: SalesFormletterWarehousePickingListFormPrintingConfigurationEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Picking list form printing configurations in SalesAndMarketing

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Picking list form printing configurations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsInventoryStatusIdDisplayed](#IsInventoryStatusIdDisplayed)||<a href="SalesFormletterWarehousePickingListFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity</a>|
|[IsItemBatchNumberDisplayed](#IsItemBatchNumberDisplayed)||<a href="SalesFormletterWarehousePickingListFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity</a>|
|[IsItemSerialNumberDisplayed](#IsItemSerialNumberDisplayed)||<a href="SalesFormletterWarehousePickingListFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity</a>|
|[IsLicensePlateNumberDisplayed](#IsLicensePlateNumberDisplayed)||<a href="SalesFormletterWarehousePickingListFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity</a>|
|[IsProductColorIdDisplayed](#IsProductColorIdDisplayed)||<a href="SalesFormletterWarehousePickingListFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity</a>|
|[IsProductConfigurationIdDisplayed](#IsProductConfigurationIdDisplayed)||<a href="SalesFormletterWarehousePickingListFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity</a>|
|[IsProductSizeIdDisplayed](#IsProductSizeIdDisplayed)||<a href="SalesFormletterWarehousePickingListFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity</a>|
|[IsProductStyleIdDisplayed](#IsProductStyleIdDisplayed)||<a href="SalesFormletterWarehousePickingListFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity</a>|
|[IsProductVersionIdDisplayed](#IsProductVersionIdDisplayed)||<a href="SalesFormletterWarehousePickingListFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity</a>|
|[IsPickingSiteIdDisplayed](#IsPickingSiteIdDisplayed)||<a href="SalesFormletterWarehousePickingListFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity</a>|
|[IsPickingWarehouseIdDisplayed](#IsPickingWarehouseIdDisplayed)||<a href="SalesFormletterWarehousePickingListFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity</a>|
|[IsPickingWarehouseLocationIdDisplayed](#IsPickingWarehouseLocationIdDisplayed)||<a href="SalesFormletterWarehousePickingListFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity</a>|
|[InventDimPickingList](#InventDimPickingList)||<a href="SalesFormletterWarehousePickingListFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity</a>|
|[DocumentAttachmentDisplayRule](#DocumentAttachmentDisplayRule)||<a href="SalesFormletterWarehousePickingListFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity</a>|
|[DisplayedDocumentAttachmentTypeCode](#DisplayedDocumentAttachmentTypeCode)||<a href="SalesFormletterWarehousePickingListFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity</a>|
|[BackingTable_CustFormletterParametersRelationshipId](#BackingTable_CustFormletterParametersRelationshipId)||<a href="SalesFormletterWarehousePickingListFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesFormletterWarehousePickingListFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity</a>|

### <a href=#IsInventoryStatusIdDisplayed name="IsInventoryStatusIdDisplayed">IsInventoryStatusIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryStatusIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsItemBatchNumberDisplayed name="IsItemBatchNumberDisplayed">IsItemBatchNumberDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsItemBatchNumberDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsItemSerialNumberDisplayed name="IsItemSerialNumberDisplayed">IsItemSerialNumberDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsItemSerialNumberDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLicensePlateNumberDisplayed name="IsLicensePlateNumberDisplayed">IsLicensePlateNumberDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLicensePlateNumberDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductColorIdDisplayed name="IsProductColorIdDisplayed">IsProductColorIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductColorIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductConfigurationIdDisplayed name="IsProductConfigurationIdDisplayed">IsProductConfigurationIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductConfigurationIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductSizeIdDisplayed name="IsProductSizeIdDisplayed">IsProductSizeIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductSizeIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductStyleIdDisplayed name="IsProductStyleIdDisplayed">IsProductStyleIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductStyleIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductVersionIdDisplayed name="IsProductVersionIdDisplayed">IsProductVersionIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductVersionIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPickingSiteIdDisplayed name="IsPickingSiteIdDisplayed">IsPickingSiteIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPickingSiteIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPickingWarehouseIdDisplayed name="IsPickingWarehouseIdDisplayed">IsPickingWarehouseIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPickingWarehouseIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPickingWarehouseLocationIdDisplayed name="IsPickingWarehouseLocationIdDisplayed">IsPickingWarehouseLocationIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPickingWarehouseLocationIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventDimPickingList name="InventDimPickingList">InventDimPickingList</a>

First included in: SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimPickingList attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentAttachmentDisplayRule name="DocumentAttachmentDisplayRule">DocumentAttachmentDisplayRule</a>

First included in: SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentAttachmentDisplayRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayedDocumentAttachmentTypeCode name="DisplayedDocumentAttachmentTypeCode">DisplayedDocumentAttachmentTypeCode</a>

First included in: SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayedDocumentAttachmentTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CustFormletterParametersRelationshipId name="BackingTable_CustFormletterParametersRelationshipId">BackingTable_CustFormletterParametersRelationshipId</a>

First included in: SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CustFormletterParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/CustFormletterParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Parameter/CustFormletterParameters.cdm.json/CustFormletterParameters</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/CustFormletterParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/SalesFormletterWarehousePickingListFormPrintingConfigurationEntity (this entity)  

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
